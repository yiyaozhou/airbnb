# Analysis using data from Airbnb
## Review Analysis
Using the reviews provided in the csv file called “reviews.csv”, which is available in GitHub in compressed form. This file contains approximately 178,000 reviews of properties in the Boston area. In this file, we have very little information about the properties—we really just have a date and a review. I used qdap, tm, tidytext and RWeka to perform an analysis.
0.	Set a random seed before Step 1 so that the results are fully reproducible.
1.	Because the number of reviews is so enormous, select a random subset of 1,000 reviews for analysis in this case.
2.	Perform the usual cleaning steps of removing numbers, punctuation, and stop words. The document briefly discusses the team decisions about adding or dropping stop words.
3.	Use TfIdf weighting to create a TermDocument Matrix. In a sentence, report on the dimensions of the resulting matrix (#rows, #columns).
4.	Create and display a well-labeled bar chart of the 15-20 most frequent terms in the reviews. 
5.	Identify the most common bigrams in your sample. 
6.	Find word associations (findAssocs() in tm) and create a word network plot to find words associated with the term “location”.
7.	Use the BING lexicon to assign positive or negative sentiments to terms, and split your sample into positive and negative comments. Make a pyramid plot to compare the most common terms in positive vs. negative reviews. 
8.	Repeat the prior step using the FINN lexicon.
9.	Consider and discuss the merits of the two lexicons in this use case. Create a comparison cloud that contrasts the positive and negative terms in your sample. 
11.	Finally, draw a conclusion:  Are these differences between positive and negative Airbnb review?  Are positive and negative reviews equally common?  Are they comparable in intensity?
