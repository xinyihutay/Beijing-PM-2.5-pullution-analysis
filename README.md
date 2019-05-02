# Beijing-PM-2.5-pullution-analysis

Columbia University Spring 2019 GR5223 group project

**Team members:**

Xinyi Hu: xh2383

Xinge Jia: 

Nikita Tourani:nrt2117


**What is your main question/topic of interest for the group project? Why have you chosen this question/topic?**

The data set that we are going to use is downloaded from https://archive.ics.uci.edu/ml/datasets/Beijing+PM2.5+Data. In this data set, hourly PM2.5 data of US Embassy in Beijing has been collected. The data set also includes meteorological data such as dew point, temperature, cumulated hours of rain etc.

In this group project, our aim is to understand how these factors influence(interact with) the value of PM2.5 and try to propose some ideas about how to reduce PM2.5.

The reason why we are interested in these questions is that air pollution problem has been an important and unsolved issue in China for years. Two members of our team are from China and both of them have suffered from very unhealthy level of PM2.5. Thus, we want to know more about PM2.5 in a statistical way and attempt to find remedy for this issue.

**What types of information/data are you planning on using in your project?**

The data set that we are going to use is a multivariate data set including both categorial data and numerical data. Besides, this is a time-series data recorded per hour per day from 2010 to 2014.

**How are your planning to carry out the analysis of the data/the project, i.e. which software/methods do you plan to use and, if applicable, what are you expecting to observe?**

In this project, we will use R to perform the analysis. And since it is a time-series data set, we will apply time series related methodologies to do the analysis.

**Ideas:**

Separate PM2.5 values into different levels according to *Air Quality Guide for PM2.5: https://www.cnn.com/2017/05/04/asia/beijing-sand-storm-pollution-beyond-index/index.html*, and the cluster months in each of the four years, to see the pattern that in which period of the year, the value of PM2.5 is high. Similarly, find out that within 24 hours, how the PM2.5 value changes. (Some simple data exploring skills, just sort the data, easy)

Summarize some overview statistics about PM2.5, like the numbers of days under each PM2.5 level.

How other factors influence the levels of PM2.5? (Dew, pressure, wind, rain etc.) Analyze their correlation with PM2.5, maybe ,do regression/classification, trian the model(cross-validation).

After understanding the influences of these factors have on PM2.5, try to come up with some approaches that could lower the value of PM2.5(improve air quality).

This folder is orgarnized as follows.

```
proj/
├── code/
├── data/
├── document/
└── reference/
```

Please see each subfolder for a README file.
