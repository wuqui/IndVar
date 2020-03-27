# _That's cool_. Computational sociolinguistic methods for investigating individual lexico-grammatical variation

## Script for data retrieval and processing

Hans-Jörg Schmid (1),  
Quirin Würschinger (1),  
Sebastian Fischer (2),  
Helmut Küchenhoff (2)  

(1) Department of English and American Studies, LMU Munich, Germany  
(2) Department of Statistics, LMU Munich, Germany  


### Functionality

* this notebook parses the XML version of BNC2014,
* calculates total counts for texts, speakers and words in the corpus,
* performs queries for the target pattern `that's ADJ` and stores all hits,
* merges hits with semantic category descriptions from the USAS tagset,
* merges hits with metadata for speakers and conversations from the spreadsheets provided by BNC2014,

Outputs files are stored in `out/`.


### Correspondence

* regarding the paper: <hans-joerg.schmid@lmu.de>
* regarding this notebook: <q.wuerschinger@lmu.de>
