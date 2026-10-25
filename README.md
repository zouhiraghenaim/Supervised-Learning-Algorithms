# Supervised Learning Algorithms

An educational repository dedicated to implementing fundamental machine learning algorithms as part of practical lab works (TPs) using Python and Scikit-Learn.

---
## 📂 Repository Structure

The project is organized into dedicated directories to maintain a clean workspace:

*   📂 **[TP1_Linear_Regression](./TP1_Linear_Regression):** Contains files related to the first practical assignment on Linear Regression:
    *   `Simple_Linear_regression_model.ipynb` — Implementation of a simple linear regression model.
    *   `TP1_Linear_Regression_Load_the_Dataset_from_GitHub.ipynb` — Guide on fetching the dataset directly from GitHub.
    *   `StudentPerformanceFactors.csv` — The dataset used for predicting student performance factors.
*   📂 **[TP2_Logistic_Regression](./TP2_Logistic_Regression):** Contains files and models related to the second practical assignment on Logistic Regression for classification tasks.

* **📁 TP4_Support_Vector_Machines:** Contains files and applications on Support Vector Machines (SVM) for advanced classification tasks:
  * `TP04_01_SVM___Support_Vector_Machines.ipynb` — First practical assignment on SVM classification.
  * `TP04_02_SVM_using_Multiple_Features.ipynb` — Comprehensive application of SVM using multiple dataset features.
  * `Simple_SVM.csv` & `pima_indians_diabetes.csv` — Datasets used for modern classification experiments.

---

## Theoretical Overview

### 1. Linear Regression
Used to predict a continuous target value based on given input features. The goal is to fit a line (or hyperplane) that minimizes the difference between predicted and actual values using the Mean Squared Error (MSE) loss function and Gradient Descent optimization.

$$\hat{y} = w_0 + w_1 x_1 + w_2 x_2 + \dots + w_n x_n$$

### 2. Logistic Regression
Used for binary classification problems (e.g., pass/fail). It maps the linear model outputs to a probability value between 0 and 1 by passing it through the Sigmoid Function.

$$P(y=1\vert{}x) = \sigma(w^T x) = \frac{1}{1 + e^{-w^T x}}$$

### 3. Support Vector Machines (SVM)
A powerful classification algorithm that searches for the optimal separating hyperplane which maximizes the margin between different data classes. It uses various kernel functions (like Linear, RBF, or Poly) to handle non-linear decision boundaries.

---

##  Tools & Libraries
* **Language:** Python 3
* **Environment:** Google Colab / Jupyter Notebooks
* **Key Packages:** `scikit-learn` • `pandas` • `numpy` • `matplotlib` • `seaborn`

---
 **Author:** **Zouhira Ghenaim**
