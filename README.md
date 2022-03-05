# DiabetesPredNaiveBayes
This dataset (diabetes,csv) contains 768 records of diebetic patients with 9 attributes of each record.
Given script first defines information of dataset (dimension, information, description) and also check for null values as this phase is preprocessing. If there is any *nan* value, it will be replaced with 0 as we are cleaning data.
# Outlier Detection
Outlier detection for each attribute is visualize using box plot graph from seaborn module.
And also perform clipping for outliers in dataset.
# Model Training
Dataset is then divided into training testing with ratio of 7:3. And import Naive Bayes model from:
*from sklearn.naive_bayes import GaussianNB*
Then training data is being fed to model.
And evalute model prediction using testing data.
