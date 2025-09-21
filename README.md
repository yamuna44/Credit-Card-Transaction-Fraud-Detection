🏦 Credit Card Transaction Fraud Detection






📌 Project Overview

Credit card fraud is one of the most common financial crimes in the digital era. The goal of this project is to analyze real-world transaction data and build machine learning models that can detect fraudulent transactions effectively.

This project involves:

Data preprocessing & cleaning

Exploratory Data Analysis (EDA)

Model training & evaluation

Visual insights for fraud detection patterns

🎯 Objective

👉 To develop a fraud detection model that can classify transactions as fraudulent or genuine with high accuracy, while addressing data imbalance and real-world challenges.

📂 Dataset

Dataset: Credit card transaction dataset (anonymized features).

Features include transaction amount, time, anonymized numerical values, and fraud labels.

Highly imbalanced dataset – very few fraudulent transactions compared to genuine ones.

🔎 Exploratory Data Analysis (EDA) Performed

Checked for missing values & data imbalance.

Distribution analysis of Amount and Time variables.

Correlation heatmap to identify important features.

Boxplots & histograms to detect outliers.

Fraud vs. Non-Fraud comparison using bar charts.

📊 Key Findings:

Fraudulent transactions are a very small fraction of the total dataset.

Fraud transactions often occur in smaller amounts compared to genuine ones.

Some anonymized features show strong correlation with fraud labels.

🤖 Machine Learning Models Used

The following models were implemented and compared:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

XGBoost Classifier

Support Vector Machine (SVM)

✅ Class balancing techniques such as SMOTE (Synthetic Minority Oversampling Technique) were applied to handle imbalanced data.

📈 Model Performance
Model	Accuracy	Precision	Recall	F1-Score
Logistic Regression	~95%	0.92	0.88	0.90
Decision Tree	~94%	0.90	0.87	0.88
Random Forest	99%	0.98	0.97	0.97
XGBoost	99%	0.98	0.97	0.97
SVM	~97%	0.95	0.91	0.93

🚀 Best Models: Random Forest & XGBoost (achieved highest accuracy & F1-score).

📊 Visualization Insights

Fraud vs. Non-Fraud Distribution: Highly imbalanced data.

Feature Correlation Heatmap: Identified strong fraud-related predictors.

Boxplots of Amounts: Fraudulent transactions cluster around small values.

ROC Curve & AUC Score: Best models achieved AUC > 0.99.

🛠️ Tech Stack

Language: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Imbalanced-learn

🚀 How to Run
# Clone this repository
git clone https://github.com/your-username/Credit-Card-Fraud-Detection.git

# Navigate to project folder
cd Credit-Card-Fraud-Detection

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook Credit_Card_Transaction_Fraud_Detection.ipynb

📌 Future Work

Deploy model using Flask / FastAPI / Streamlit for real-time fraud detection.

Use Deep Learning (LSTMs/Autoencoders) for anomaly detection.

Implement feature engineering to improve recall for fraud detection.

👤 Author

Your Name
🔗 LinkedIn
 | GitHub
