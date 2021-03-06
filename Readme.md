# Vectors in Search

Dice.com code for implementing the ideas discussed in the [Vectors in Search](https://sched.co/FkM3) talk from the Activate 2018 conference, by Simon Hughes ( Chief Data Scientist, Dice.com )

## Directory Structure
- **python**
  - Code for implementing the k-means tree, LSH sim hash and vector thresholding algorithms, and indexing and searching vectors in solr using these techniques.
- **solr_plugins**
  - Java code for implementing the custom similarity classes and payloadEdismax parser described in the talk.
- **solr_configs**
  - Xml snippets for importing the solr plugins from the 'solr_vectors_in_search_plugins' java code.

## Implementation Details
- Solr Version - 7.5
- Python Version - 3.x+ (3.5 used)

## Tutorial
I will add a notebook shortly that outlines how to use this code to load and search vectors efficiently within solr.

## Links
* [Slides from the talk](https://www.slideshare.net/lucidworks/vectors-in-search-towards-more-semantic-matching-simon-hughes-dicecom)
* [Video of the Talk](https://www.youtube.com/watch?v=rSDqhGn_8Zo&list=PLU6n9Voqu_1HW8-VavVMa9lP8-oF8Oh5t&index=20&t=0s)

