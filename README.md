# Credit-Card-Fraud-Detection-Using-Machine-Learning
PROJECT OVERVIEW

Welcome to the PROJECT Detection OF FRAUD TRANSACTIONS in Banks! The Business problem is here to tap which transaction is a normal & which transaction is a fraudulent transaction. The aim of this project is to build a classifier that can detect credit card fraudulent transactions. We will use a variety of machine learning algorithms that will be able to discern fraudulent from non-fraudulent one. By the end of this machine learning project, you will learn how to implement machine learning algorithms to perform classification. Credit card fraud is when when someone uses your credit card or credit account to make a purchase you didn't authorize. This activity can happen in different ways: Fraudsters can also steal your credit card account number, Pin and security code to make unauthorized transactions without needing your physical credit card.

The challenge is to recognize fraudulent credit card transactions so that the customers of credit card companies are not charged for items that they did not purchase.In this project, you will learn how to Detect the Fraud Transactions using Machine Learning Algorithms.

Total Row Size : 2,84,807 with 31 features inorder to reduce the computational issues we go with sampling.

Total percentage(%) of fraudulent transactions = 0.1727

MAIN CHALLENGES INVOLVED IN CREDIT CARD FRAUD DETECTION ARE:

(1) Enormous Data is processed every day and the model build must be fast enough to respond to the scam in time.

(2) Imbalanced Data i.e most of the transactions (99.8%) are not fraudulent which makes it really hard for detecting the fraudulent ones

(3) Data availability as the data is mostly private.

(4) Misclassified Data can be another major issue, as not every fraudulent transaction is caught and reported.

(5) Adaptive techniques used against the model by the scammers.

** Key Terms **

(1) Balanced v/s Unbalanced dataset.

(2) PCA (Principle Component Analysis) Transformation.

(3) LOF (Local Outlier Factor) Algorithm.

(4) Isolation Forest Algorithm.

(5) SVM (support Vector Machine).

INSTRUCTIONS TO THE PROJECT:

Use Jupyter Notebook or GoogleColab (use this link to download the dataset https://www.kaggle.com/mlg-ulb/creditcardfraudfrom kaggle.com )
Importing the Datasets
Data Exploration
Data Manipulation
Data Modelling
Fitting Isolation Forest Algorithm Model
Fitting Support Vector Machine Model
*** Anamolys ***

The algorithm is based on the fact that anamolys are data points which are different . As a result of these properties, Anamolys are susceptible to a mechanism called as "ISOLATION"

This method is highly useful & it is fundamentally different from all other existing models.

Moreover the method is an algorithm with low linear time complexity and a small memory requirement.

*** Balanced v/s Unbalanced Datasets***

The transactions which are done in good patterns is Balanced Datasets.

The transactions which are done in different Unbalanced Datasets.

*** Isolation Forest ***

The Isolation Forest Algorithm isolates observations by randomly selecting a feature & then randomly selecting a split value between Maximum & Minimum values of the selected feature. The logical argument goes isolating anamoly observations is easier because only a few conditions are needed to seperate those cases from the normal observations. On the other hand isolating normal observations required more conditions.

An anamoly code can be calculated a no. of conditions required to seperate given observation.

*** Local Outlier Factor ***

The Local Outlier Factor Algorithm is an unsupervised outlier detection method which computes the local density deviation of a given data point with respect to its neighbours.

The no. of neighbours considered is typically choosen with the following parameters.

If greater than the minimum no. of objects a cluster has to contain, the other objects can be considerd as outliers relative to the cluster.

*** Support Vector Machine ***

Support Vector Machine is a powerful model which is capable of performing linear (or) Non - Linear classification, regression & also for outlier detection.
CONCLUSION
Comparing the errors in models
Isolation forest detected 73 errors

Where as Local Outlier Factor detects 95 errors

Support Vector Machine has detected 8516 errors

Accuracy:

Isolation Forest detected 73 errors v/s Local Outlier Factor detecting 97 errors v/s SVM detecting 8516 errors.

Isolation Forest has a 99.74% more accurate than LOF of 99.65% and SVM of 70.09.

When comparing error precision & recall for 3 models , the Isolation Forest performed much better than the LOF as we can see that the detection of fraud cases is around 27 % versus LOF detection rate of just 2 % and SVM of 0%.

So overall Isolation Forest Method performed much better in determining the fraud cases which is around 30%.

We can also improve on this accuracy by increasing the sample size or use deep learning algorithms however at the cost of computational expense.We can also use complex anomaly detection models to get better accuracy in determining more fraudulent cases
