# Keywords Visualization Tool

This tool extracts keywords from an idea description and visualizes them in a 2D space using sentence embeddings and dimensionality reduction.

**How it works:**

1.  Input an idea description.
2.  The tool extracts keywords using Gemini 1.5 Flash.
3.  Sentence embeddings for keywords are generated using SentenceTransformer.
4.  Embeddings are reduced to 2D using PCA.
5.  Keywords are plotted as points in a 2D space using Plotly, revealing relationships and clusters.

**Libraries used:**

*   langchain
*   google-generativeai
*   matplotlib
*   sentence-transformers
*   scikit-learn
*   plotly
*   numpy

**Project Team:**

OUAAZIZ MOUHCINE, MOUNSSIF CHOUAIB, FAZZA ABDELLAH, EL BARAGHI OUSSAMA, and FAOUZI KAMAL
