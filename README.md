# Depression_Detection_using_Twitter_tweets_data
Detecting Depression using Twitter tweets data. Used Machine Learning Algorithms like Support Vector Machines, Decision Trees.

Introduction -
Depression is a prevalent mental health disorder affecting millions of people worldwide. It can
have serious consequences on individuals' lives, including impaired functioning, decreased
quality of life, and increased risk of suicide. Detecting depression early and accurately is crucial
for timely intervention and treatment. With the advent of social media platforms like Twitter,
individuals often express their thoughts, emotions, and experiences openly, including those
related to mental health. Analyzing tweets data presents a promising opportunity for detecting
signs of depression and providing support to those in need.
Motivation -
Availability of Twitter Data on various platforms like Kaggle. Twitter has an API called Twint,
Tweepy that can be used to scrape the tweet data and makes it easier to classify the tweet as
positive or negative which can be further analyzed to see whether the user is facing any
symptoms of Depression. Early detection of symptoms is always beneficial as it allows timely
support and treatment as most of the times it goes untreated and becomes severe. Twitter data
analysis can be applied across various fields, including healthcare, marketing, finance, and
social sciences, contributing to interdisciplinary research and innovation.

DATA UNDERSTANDING
In the data understanding phase, we plan to utilize the various Twitter APIs to collect a
substantial volume of tweets related to diverse topics, with a specific focus on mental health.
This data will encompass a mix of positive and negative sentiments, reflecting a broad spectrum
of users' emotional states.
The General tweet data was taken from Kaggle which contained 10000 entries. The Dataset for
Depressive tweets was taken from multiple sources. The initial plan was to fetch all the data
from Twint or Tweepy API which is a very good platform to get all the required tweets data. But
due to change in Twitter Policies which has now become X, all the APIs are not working and
everything has been made chargeable. So as an alternative, there is a platform Apify which
provides a service to get some tweets using Twitter Scraper. A few tweets related to depression
have been fetched from this service.
There are already a few datasets available containing Depressive tweets. One of the platform
was Dataverse which contained a dataset having 57000 tweets out of which 24391 were
depressive tweets, they judged it based on negation words. Source of this data is
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/CMDF4U . Another
dataset of these kind of tweets was found on kaggle which had 20000 entries,
https://www.kaggle.com/datasets/infamouscoder/mental-health-social-media. Based on these
findings, a good amount of data for tweets related to mental health issues were found for
processing and further model building.

CONCLUSION:
In conclusion, the model development phase encompassed the implementation and evaluation
of Support Vector Machines (SVM) and Decision Trees to classify tweets as either normal or
indicative of depressive symptoms. Both models exhibited impressive accuracies, with SVM
achieving 99.26% and Decision Tree demonstrating a comparable performance. These results
underscore the efficacy of these approaches in accurately categorizing tweets related to mental
health.
However, it's imperative to acknowledge the potential risk of overfitting, particularly given the
high accuracy achieved on the test set. Further scrutiny and validation of the models are
essential to ensure their generalizability and reliability in real-world scenarios. By addressing
potential overfitting concerns and refining the models accordingly, we can enhance their
robustness and applicability for practical deployment.
