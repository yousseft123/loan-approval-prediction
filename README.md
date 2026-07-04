# 🏦 Loan Approval Prediction

<p align="center">
<b>Python • Machine Learning • Scikit-Learn • Data Analysis</b>
</p>

Predict whether a loan application will be **approved** or **rejected** using applicant demographic and financial information.

This project demonstrates an end-to-end machine learning workflow, including **data preprocessing**, **exploratory data analysis (EDA)**, **feature engineering**, **classification modeling**, **model evaluation**, and **loan prediction**.

---

## 📑 Table of Contents

- Project Overview
- Project Objectives
- Technologies Used
- Repository Structure
- Dataset
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Development
- Model Evaluation
- Prediction Example
- Key Findings
- Skills Demonstrated
- Author

---

# 📌 Project Overview

Loan approval is one of the most common classification problems in the financial sector. This project predicts whether a loan application will be approved based on an applicant's demographic and financial information.

The notebook demonstrates a complete machine learning workflow from data preprocessing to model evaluation and prediction.

---

# 🎯 Project Objectives

- Predict loan approval status.
- Clean and preprocess the dataset.
- Explore applicant characteristics using EDA.
- Create meaningful features to improve prediction.
- Train and compare multiple machine learning models.
- Evaluate model performance using standard metrics.
- Predict loan approval for new applicants.

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# 📂 Repository Structure

```
Loan-Prediction
│
├── Loan_Prediction.ipynb
└── README.md
```

---

# 📊 Dataset

The dataset contains applicant demographic and financial information, including:

- Gender
- Married
- Dependents
- Education
- Self Employed
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area
- Loan Status

---

# 🧹 Data Preprocessing

The preprocessing stage includes:

- Handling missing values
- Duplicate checking
- Data type conversion
- Encoding categorical variables
- Feature scaling
- Data preparation for machine learning

---

# 📈 Exploratory Data Analysis (EDA)

The notebook includes visualizations such as:

- Loan Status Distribution
- Loan Approval by Education
- Loan Approval by Gender
- Loan Approval by Property Area
- Correlation Heatmap
- Total Income Distribution
- Loan Amount Distribution

---

# ⚙️ Feature Engineering

Several new features were created to improve model performance:

- Total Income
- Log Transformation
- Income-to-Loan Ratio

These features reduce skewness and provide additional information for the models.

---

# 🤖 Model Development

The following classification models were implemented:

### Logistic Regression

A baseline linear classification model trained on standardized features.

### Random Forest

An ensemble learning algorithm capable of capturing nonlinear relationships and improving prediction accuracy.

---

# 📊 Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Feature Importance

---

# 🔮 Prediction Example

The trained Random Forest model predicts whether a new loan application will be:

- ✅ Approved
- ❌ Rejected

The model also provides the probability of loan approval.

---

# 📈 Key Findings

- Credit History is the most influential feature in loan approval prediction.
- Random Forest achieved higher predictive performance than Logistic Regression.
- Feature engineering improved model performance.
- Most approved applications had a positive credit history.
- Income-related features also contributed significantly to prediction accuracy.

---

# 💼 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning
- Classification
- Model Evaluation
- Data Visualization
- Python Programming
- Scikit-Learn

---

# 👨‍💻 Author

**Youssef Tarek**

Data Analyst | Machine Learning Enthusiast
