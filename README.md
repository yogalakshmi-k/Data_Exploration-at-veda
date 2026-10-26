# 📊 Day 17: Dataset Exploration using Pandas

## 📌 Internship Details
- **Internship:** AI & ML Internship
- **Organization:** Veda Technology
- **Day:** 17 of 45
- **Task:** Dataset Exploration
- **Domain:** Artificial Intelligence & Machine Learning

## 🎯 Objective
To explore a dataset using Python and Pandas to understand its structure, dimensions, column names, data types, and statistical characteristics before building a Machine Learning model.

## 🛠️ Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Google Colab
- Jupyter Notebook

## 📂 Dataset
**Dataset Name:** Iris Dataset

The Iris dataset contains measurements of three species of iris flowers:
- Setosa
- Versicolor
- Virginica

It includes four numerical features:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

## 🔍 Tasks Performed
1. Loaded the Iris dataset using Scikit-learn.
2. Explored the first five rows using `head()`.
3. Displayed the last five rows using `tail()`.
4. Checked the dataset dimensions using `shape`.
5. Examined column names using `columns`.
6. Inspected data types and non-null counts using `info()`.
7. Generated statistical summaries using `describe()`.
8. Identified numerical and categorical columns.
9. Checked for missing values using `isnull().sum()`.

## 📈 Dataset Information
- **Total Rows:** 150
- **Total Columns:** 5
- **Numerical Columns:** 4
- **Categorical Columns:** 1
- **Missing Values:** 0

## 💡 Key Observations
1. The dataset contains 150 observations and 5 columns.
2. Four columns contain numerical measurements of iris flowers.
3. The `species` column represents the three iris flower categories.
4. The `describe()` function provides statistical information such as mean, standard deviation, minimum, and maximum values.
5. The `head()` and `tail()` functions display the first and last five records, respectively.
6. No missing values were found in the dataset.
7. Exploring the dataset helps us understand its characteristics before applying Machine Learning algorithms.

## 💻 Python Libraries Used
```python
import pandas as pd
from sklearn.datasets import load_iris
```

## ❓ Interview Questions

**1. Why should a dataset be explored before modeling?**

Dataset exploration helps us understand the structure, data types, missing values, and statistical characteristics of the data before training a model.

**2. What does `DataFrame.shape` return?**

It returns a tuple containing the number of rows and columns in a DataFrame.

**3. What information does `info()` provide?**

It displays column names, non-null counts, data types, and memory usage.

## ✅ Deliverables
- Dataset exploration notebook
- Dataset dimensions and column information
- At least five observations about the dataset

## 🏁 Conclusion
This task helped me understand how to explore a dataset using Pandas. I learned to inspect dataset dimensions, identify column types, generate statistical summaries, and check for missing values before proceeding with Machine Learning.

---
⭐ **Day 17 of 45 — AI & ML Internship Journey**

#Python #Pandas #MachineLearning #ArtificialIntelligence #DataAnalysis #VedaTechnology #Internship
