# Projet IC05

---
## amazon

#### Description :
This projet consists in two parts:
* First, the data is scraped from an online store in order to build links between items.
* Then, grap representation of the data.

#### Members :
* Daniel Artchounin
* Camil Sadiki
* Pierre Zins

#### Files :
- scraper.py : scrap products from Amazon which are often bought together. Create a file amazon_data with all the data.
- transform.py : convert the result of the scraping into GEXF file usable with Gephi
- append.py : add new data (file) in the main data file
- amazon_data : data scraped
- amazon_data_analysis_website : website of the project
- graphs : results 3 versions :
	- picture 
	- gephi file 
	- SigmaJS version


---

## l1_foot

#### L1 matches of the last 4 seasons

- 2012/2013
- 2013/2014
- 2041/2015
- 2015/2016


An oriented edge from team A to team B
- if the result attribute is > 0 : A has more victory against B
- if the result attribute is < 0 : B has more victory against A
- if the result attribute is = 0 : A and B have equal victories/defeats/draws


#### files : 
- gps.data : GPS coordinate of French L1 cities
- foot.py : scrap data about L1 results
- format.py : create GEFX file with GPS coordinate from data scraped
- data_l1.xml : data scraped about L1 results
- gephi_data_l1.gexf : formatted data
- l1_moyenne.gephi : result L1 mean (victory, defeat, draw)

---

# wikipedia
- Scraping data from Wikipedia
- Visit every links in the wikipedia page
- Start with one or several key pages
- Give a graph view with links between related words


