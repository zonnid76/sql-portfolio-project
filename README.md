# 1. UMG Data Analyst SQL Project
# 2. Project Objective
## a. The Problem
How can the potential for a song to become a top hit be estimated?
## b. Approach to Solving the Problem
To solve the problem, I am using data about song characteristics to find the average characteristics of hit songs.
Knowing this, the average characteristics of hit songs can then theoretically be used to predict the hit-making potential of songs, as a song should be more likely to become a hit if its characteristics are similar to those of existing top hits.
# 3. Job Description
## a. UMG Data Analyst Details
Universal Music Group (UMG) is the world's leading music company, owning and operating a broad array of businesses in more than 60 countries, including many record labels, such as Capitol Records, Def Jam Records, Island Records, and Republic Records.
My project is particularly based on the data analyst role at UMG.
Main points in the description for job postings of this role include using data-driven methods to discover, track, and analyze developing songs and artsts, as well as using intern and external data sources to perform detailed analysis that can leverage data for decision-making.
They are looking for somebody who is proficient on both Python and SQL, has experience working with music data, and has the ability to provide answers to loosely defined questions and provide actionable insights.
## b. Project Relationship to Job Posting
Given the job description, this project would help qualify me for the role.
If I can successfully leverage data of song characteristics to provide actionable insights on how to approach investing in artists, using SQL and Python, I would then meet the exact description/qualifications that UMG is looking for.
# 4. Data
## a. Source
I utilized Spotify's API to collect data of songs from 53 different playlists, each having 100 top hit songs from each year, spanning from 1970 through 2022.
## b. Characteristics
The song data that I collected for each track are: 'track_id', 'chart_year', 'track_name', 'artist', 'album', 'danceability', 'energy', 'track_key', 'loudness', 'speechiness', 'acousticness', 'instrumentalness', 'liveness', 'valence', 'tempo', 'duration_ms', and 'time_signature'.
# 5. Notebooks
## a. Data Collection Notebook: https://github.com/zonnid76/sql-portfolio-project/blob/b3664e10a890168efab722073362425c56b643f9/data_collection.ipynb
In the data collection notebook, I imported libraries in order to easily connect to Spotify's API, extract song data of top hits, and insert the data into a MySQL database.
## b. SQL Analysis Notebook: https://github.com/zonnid76/sql-portfolio-project/blob/b3664e10a890168efab722073362425c56b643f9/sql_analysis.ipynb
In the SQL analysis notebook, I ran 5 exploratory SQL queries, 1 primary SQL query, and 2 secondary SQL queries in order to solve the problem and determine the general characteristics that make up a top hit, which can then be used to predict top-hit-potential of future songs.
# 6. Future Improvements
## a. Adding a Comparison Group
To continue this project, I would next add data from a large catalog of random songs, in order to compare the random song data to that of the top hits, to see how they differ.
