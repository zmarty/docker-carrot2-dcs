# Carrot2 Document Clustering Server (DCS) Docker Image

Docker image that contains the **[Carrot2 Document Clustering Server](http://project.carrot2.org/download-dcs.html)** (text clustering api server).

**What is Carrot2**

Carrot2 is an Open Source Search Results Clustering Engine. It can automatically organize small collections of documents (search results but not only) into thematic categories.

**What is Carrot2 Document Clustering Server (DCS)**

Carrot2 Document Clustering Server (DCS) exposes Carrot2 clustering as a REST service. It can cluster documents from an external source (e.g. a search engine) or documents provided directly as an XML stream and returns results in XML or JSON formats.

You can use Carrot2 Document Clustering Server to:
* Integrate Carrot2 with your non-Java software.
* Build a high-throughput document clustering system by setting up a number of load-balanced instances of the DCS.

Carrot2 Document Clustering Server features include:
* **XML and JSON response formats.**  Carrot2 Document Clustering Server can return results both in XML and JSON formats. JSON-P (with callback) is also supported.
* **Various document sources included.**  Carrot2 Document Clustering Server can fetch and cluster documents from a large number of sources, including major search engines and indexing engines (Lucene, Solr).
* **Direct XML feed.**  Carrot2 Document Clustering Server can cluster documents fed directly in a simple XML format.
* **PHP and C# examples included.**  Carrot2 Document Clustering Server ships with ready-to-use examples of calling Carrot2 DCS services from PHP (version 5), C#, Ruby, Java and curl.
* **Quick start screen.**  A simple quick start screen will let you make your first DCS request straight from your browser.

![Carrot2 DCS screenshot](http://download.carrot2.org/head/manual/img/dcs.png)

**How to run it**

```
docker run -it --rm zmarty/carrot2-dcs
```

If you are new to Docker, please note that due to the rm command line argument above all your file changes within the container will be lost.
