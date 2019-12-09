# SMS Spam-Filtering

# Introduction
This project is my first natural language processing project. The purpose of this study is to optimize a classification model to predict spam or ham (legitimate) SMS text message from the text contents via text mining methods. The data set used in this study is a collection of 5,574 English, real and non-enconded messages, tagged according to being spam or ham (legitimate).  Data wrangling is performed followed by data pre-processing with tokenization and stemming to extract features from text contents to create feature matrix. Each feature appears as the number counts of a word or phrase in each text message. The spam and ham classifiers are created by applying basic
data mining techniques, such as logistic regression, k-Nearest Neighbors (KNN), Gaussian naive bayesian algorithm, as well as advanced ones, such as random forest or XGBoost, to the feature matrix. Cross-validation is employed to compare different classifiers and find out the optimal one by judging the average prediction error rate. This study may provides an idea how to apply data mining techniques in
text mining research and how to optimize a classification model to discriminate spam text messages from ham text
messages.

# Findings
Bag of Words model and Bag of Words model with bigram have relatively better performance over TF-IDF model and TF-IDF model with bigram.
