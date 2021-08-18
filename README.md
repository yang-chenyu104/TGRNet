# TGRNet: A Table Graph Reconstruction Network for Table Structure Recognition
> Xue, Wenyuan, et al. "TGRNet: A Table Graph Reconstruction Network for Table Structure Recognition." arXiv preprint arXiv:2106.10598 (2021).  

This work has been accepted for presentation at ICCV2021. The preview version has released at arXiv.org (<https://arxiv.org/abs/2106.10598>). Code will be made publicly soon.
## Abstract
A table arranging data in rows and columns is a very effective data structure, which has been widely used in business and scientific research. Considering large-scale tabular data in online and offline documents, automatic table recognition has attracted increasing attention from the document analysis community. Though human can easily understand the structure of tables, it remains a challenge for machines to understand that, especially due to a variety of different table layouts and styles. Existing methods usually model a table as either the markup sequence or the adjacency matrix between different table cells, failing to address the importance of the logical location of table cells, e.g., a cell is located in the first row and the second column of the table. In this paper, we reformulate the problem of table structure recognition as the table graph reconstruction, and propose an end-to-end trainable table graph reconstruction network (TGRNet) for table structure recognition. Specifically, the proposed method has two main branches, a cell detection branch and a cell logical location branch, to jointly predict the spatial location and the logical location of different cells. Experimental results on three popular table recognition datasets and a new dataset with table graph annotations (TableGraph-350K) demonstrate the effectiveness of the proposed TGRNet for table structure recognition. Code and annotations will be made publicly available.
