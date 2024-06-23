# Analysis of Google Play Store Apps and Reviews

## Project Overview
Mobile apps are ubiquitous and lucrative, leading to a constant influx of new apps. This project provides a comprehensive analysis of the Android app market by examining over ten thousand apps from Google Play across various categories. The goal is to uncover insights that can help devise strategies to drive growth and retention.

## Data Description
The dataset consists of two files:
- **apps.csv**: Contains details of the applications on Google Play, with 13 features describing each app.
- **user_reviews.csv**: Contains 100 reviews per app, sorted by most helpful first. Each review includes three new features: Sentiment (Positive, Negative, or Neutral), Sentiment Polarity, and Sentiment Subjectivity.

## Analysis Steps

### 1. Data Cleaning
Special characters in columns like Installs and Price prevent these columns from being purely numeric. Removing these characters facilitates future calculations.

### 2. Correcting Data Types
Columns Installs and Price were initially categorized as objects due to mixed input types (digits and special characters). These columns were converted to numeric types for further analysis.

### 3. Exploring App Categories
Exploring which categories have the highest and lowest number of apps reveals that Family and Game apps dominate the market, while categories like Tools, Business, and Medical also have significant numbers.

### 4. Distribution of App Ratings
App ratings, ranging from 1 to 5, impact app discoverability and company brand image. The average app rating is 4.17, with the distribution skewed towards higher ratings.

### 5. Size and Price of an App
Examining how app size and price affect user ratings shows that most top-rated apps (ratings over 4) are between 2 MB and 20 MB in size, and the majority of apps are priced under $10.

### 6. Relation Between App Category and App Price
Different app categories demand different price ranges. Medical and Family apps are the most expensive, with some medical apps priced up to $80, while most game apps are priced below $20.

### 7. Filtering Out "Junk" Apps
Identifying and filtering out "junk" apps, which are often overpriced and serve little purpose, improves the accuracy of the analysis.

### 8. Popularity of Paid Apps vs Free Apps
Comparing the popularity of paid and free apps shows that paid apps generally have fewer installs than free apps, although the difference is not as significant as expected.

### 9. Sentiment Analysis of User Reviews
Performing sentiment analysis on user reviews determines the general mood (positive, negative, or neutral) towards each app. Free apps tend to receive harsher comments compared to paid apps, suggesting that paid apps might be of higher quality on average.

## Conclusion
The analysis of over ten thousand apps from the Google Play Store provides valuable insights that can inform future app development and marketing strategies.

## Libraries Used
- pandas
- numpy
- plotly
- seaborn
- matplotlib

