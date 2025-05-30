# ⛏️ Rock vs Mine Prediction Using Logistic Regression

This project applies Logistic Regression to classify sonar signals and determine whether the object detected is a rock or a mine. The dataset is based on sonar return data collected from undersea objects and is sourced from the UCI Machine Learning Repository via Kaggle.

## 📌 Project Overview

- Cleaned and standardized the sonar dataset
- Used `train_test_split` to divide the data into training and testing sets
- Trained a logistic regression classifier using scikit-learn
- Achieved **76% accuracy** on test data
- Visualized data using Seaborn and Matplotlib to analyze feature relationships

## 🔧 Tech Stack

- **Languages & Libraries:** Python, NumPy, Pandas, scikit-learn, Seaborn, Matplotlib
- **IDE/Tools:** Jupyter Notebook / Google Colab

## 📊 Dataset

The dataset contains 208 records with 60 sonar readings each, representing different signal returns.  
**Link:** [Kaggle – Rock vs Mine Dataset](https://www.kaggle.com/datasets/uciml/sonar-all-data)

## 📁 Folder Structure
- Rock_Mine_detection_model.ipynb
- sonar data.csv
- requirements.txt


## 🚀 How to Run

1. Clone this repository  
   `git clone https://github.com/your-username/rock-mine-prediction.git`

2. Install the required libraries  
   `pip install -r requirements.txt`

3. Open `rock_mine_prediction.ipynb` in Jupyter or Colab and run the cells

## 📈 Results

- Final model: **Logistic Regression**
- Accuracy: **76%**
- Evaluation metrics used: Accuracy 

---

**Note:** This is a beginner-level classification project intended to demonstrate the application of logistic regression on real-world sonar signal data.

