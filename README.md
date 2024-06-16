# CSV to Knowledge Graph Matching System

This repository contains a simple system for performing Cell Entity Annotation (CEA) and Column Type Annotation (CTA) on tabular data using the Wikidata knowledge graph. The system processes CSV files and matches cells to Wikidata entities and columns to Wikidata types. The results are saved in a specified format required for the SemTab 2024 challenge.

## Tasks Performed

- **Cell Entity Annotation (CEA)**: Matching individual cell values to entities in Wikidata.
- **Column Type Annotation (CTA)**: Matching entire columns to types in Wikidata.

## Dataset

The system has been tested and evaluated using the `WikidataTables2024` tables for Round 1 (located in the "Valid" folder).

Dataset link: [WikidataTables2024](https://github.com/sem-tab-challenge/2024/tree/main/data)


## Note
The results for the CEA task are very low, likely because only one ground truth was considered for each cell, unlike the multiple ground truths provided in lab session 3.
