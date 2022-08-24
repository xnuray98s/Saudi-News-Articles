# Saudi News Articles Classification
Newspapers includes a huge and important part of history, and this project contain articles that were scraped from four Saudi newspapers, that hopefully will contribute in understanding the changes in saudi arabia in the recent years. This project also include EDA on the data, summarize articles using TF-IDS and Three ML models to classify articles.

## Data

| Variable      | Description |
| ----------- | ----------- |
| url      | The url for the article       |
| title   | The title of the article       |
| author   | The author of the article        |
| content   | The content of the article        |
| section   | The category of the article        |


## Articles Count

| Newspaper      | Count |
| ----------- | ----------- |
| Okaz      | 13515       |
| Sabq   | 8350       |
| Al-Riyadh     | 2260        |
| Al-Jazirah   | 1116        |

## Conclusion
- I have found that Local and Sport were the only sections that are present in all four newspapers
- Top 4 most frequent words in Alriyadh are not Arabic
- I have trained three models which are KNN, Decision trees and SVM, and found that SVM is the best model with 79.9% precision and 81.2% accuracy