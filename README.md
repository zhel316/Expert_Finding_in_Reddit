# Expert Finding in Reddit
This project aims to find top experts and topics in a large-scale raw Reddit corpus ($\geq 1.5TB$) in the last 20 years.<br> This large-scale data project was finished on [Databrick](https://www.databricks.com/) by using `Spark`.

## File Description

- reduced_data.ipynb: extracts useful information from raw dataset.
- get_top_subrid.ipynb: selects the top 20 popular subreddits on Reddit based on the number of votes and comments.
- extract_expertise.ipynb: select the top 10 experts who received the most votes from the top 20 popular subreddits.
- extract_topic.ipynb: Analyzes the content of top popular topics from the top 20 popular subreddits by `NLP`.
- wordcloud_topic.ipynb: visualizes the popular topics by using word cloud.
- combine_json.ipynb: saves the result, and combine several parquet files into a whole CSV file.

