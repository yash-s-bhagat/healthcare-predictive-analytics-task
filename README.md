# healthcare-predictive-analytics-task
Healthcare Predictive Analytics

Project Overview

This project demonstrates a basic healthcare predictive analytics workflow using Python and machine learning. It uses a synthetic patient dataset to build a logistic regression model that predicts a sample binary disease label based on selected health and lifestyle features.

Objectives

- Analyze historical healthcare-style data.
- Prepare and preprocess data for machine learning.
- Build a simple predictive classification model.
- Evaluate the model using accuracy, precision, recall, and F1 score.
- Visualize model results and sample patterns.
- Generate summary reports for interpretation.

Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- GitHub

Repository Structure

healthcare-predictive-analytics-task/
├── data/
│   └── healthcare_patient_data.csv
├── src/
│   └── predict_disease_risk.py
├── outputs/
│   ├── model_metrics.csv
│   ├── classification_report.csv
│   ├── confusion_matrix.png
│   ├── label_rate_by_age_group.csv
│   ├── label_rate_by_age_group.png
│   ├── model_feature_coefficients.csv
│   └── top_model_coefficients.png
├── requirements.txt
└── README.md

Dataset Description

The dataset contains 300 synthetic records with the following features:

- Patient ID
- Age
- Body Mass Index (BMI)
- Smoking status
- Exercise level
- Family history
- Systolic blood pressure
- Synthetic disease label (0 or 1)

Note: The data and target labels are simulated for educational use. They do not represent real patients or a validated disease definition.

Installation

Install Python 3.9 or later, then install the required libraries:

pip install -r requirements.txt

How to Run

Run the following command from the project directory:

python src/predict_disease_risk.py

The script preprocesses the dataset, splits the data into training and testing sets, trains the logistic regression model, evaluates predictions, and saves charts and reports in the "outputs/" directory.

Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 score
- Confusion matrix
- Classification report

The dataset is divided into training and testing subsets to assess predictions on records not used to fit the model.

Output Files

- "model_metrics.csv": Overall evaluation metrics.
- "classification_report.csv": Class-level evaluation results.
- "confusion_matrix.png": Actual versus predicted labels.
- "label_rate_by_age_group.png": Sample label distribution across age groups.
- "model_feature_coefficients.csv": Model coefficients.
- "top_model_coefficients.png": Largest absolute coefficient magnitudes.

Limitations

- The dataset is synthetic and small.
- The target labels do not represent confirmed diagnoses.
- Model performance depends on the generated data and train/test split.
- Feature coefficients do not establish causation or clinical importance.
- This model has not been validated for clinical use.

Conclusion

This project demonstrates the fundamentals of healthcare predictive analytics, including data preprocessing, model training, evaluation, and visualization. It provides a starting point for learning machine learning applications in healthcare data analysis.

Author

B.Pharmacy Graduate | Healthcare and Pharmacy Data Analytics

Disclaimer

This project is for educational and internship purposes only. It must not be used to diagnose disease, recommend treatment, or make real-world clinical decisions.