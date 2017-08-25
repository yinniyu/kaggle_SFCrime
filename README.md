# kaggle_SFCrime
This is the readme file for Kaggle SF crime data prediction ( April 2016)
 
<p>This repository is created for the Kaggle SF crime prediction project. In the file name <i>SF crime(1).ipynb</i>, Bernoulli Naive Bayes method was used as the predictive model, and 
in <i>SF crime(2).ipynb</i>, XGB classifier was used and yielded better results. For both methods, weekeday was extracted from Dates column, and one-hot-encoding was performed for the categorical columns. Features used for modeling were the same for both models - mainly the neighborhoods, gps coordinate (Y), and time. For the XGB classifier, a feature importance graph was generated as part of the XGB library. Feature importance score (F score on x-axis) is a measure of how useful a feature when it comes to improving decision tree performance within the Ensemble model. Based on this graph, the location (Y-coordinate) and hours (second highest) yielded strong predictive impact in determining the probability of a crime categories</p>

![alt text](https://github.com/yinniyu/kaggle_SFCrime/blob/master/feature_importance.png)

<p> Using Tableau, a map of the crime activity is generated as shown (for interactive map, click <a href="https://public.tableau.com/shared/9G5CTJZ4Y?:display_count=yes"> here </a>).
<p align="center">
  <img src="crime_location.png" width="650"/>
</p></p>
