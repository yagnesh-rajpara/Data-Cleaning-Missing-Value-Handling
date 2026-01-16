# AI & ML Internship – Task 2  
## Data Cleaning & Missing Value Handling (Housing Dataset)

This repository contains the solution for **Task 2** of the AI & ML Internship, focusing on **data cleaning, missing value handling, visualization, and data quality analysis** using the Housing dataset.

---

## 📌 Dataset Used
- **Housing Dataset (Housing.csv)**  
  A real-world dataset containing housing-related features used for analysis and machine learning preparation.

---

## 🛠 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🎯 Task Objectives
- Identify missing values using `isnull().sum()`  
- Visualize missing data patterns  
- Handle missing values using appropriate imputation techniques  
- Drop columns with extremely high missing values  
- Validate dataset after cleaning  
- Perform advanced data quality analysis  
- Save a cleaned dataset for ML usage  

---

## 📊 Work Performed
- Checked dataset structure and data types  
- Analyzed missing values and missing percentages  
- Implemented safe visualization logic for missing values  
- Applied **median imputation** for numerical features  
- Applied **mode imputation** for categorical features  
- Dropped columns with excessive missing data  
- Performed advanced analysis:
  - Distribution plots
  - Correlation heatmap
  - Outlier detection using IQR method  
- Exported final cleaned dataset  

---

## 📁 Project Structure
```
📁 Task-2-Data-Cleaning
│
├── AI_ML_Task2_Housing_Advanced.ipynb   # Complete cleaning & analysis notebook
├── Housing.csv                          # Original dataset
├── Housing_cleaned.csv                  # Cleaned dataset (output)
└── README.md                            # Project overview
```

---

## ▶️ How to Run
1. Clone the repository  
2. Ensure `Housing.csv` is in the same directory as the notebook  
3. Open `AI_ML_Task2_Housing_Advanced.ipynb` in Jupyter Notebook / Colab  
4. Run all cells from top to bottom  

---

## ✅ Outcome
The dataset was successfully cleaned and validated. Advanced visualizations and data quality checks ensure that the dataset is **fully machine-learning ready**.

---

**Author:** Internship Candidate  
