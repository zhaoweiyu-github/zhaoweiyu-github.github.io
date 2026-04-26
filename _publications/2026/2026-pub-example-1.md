---
title:          "ChromBERT: A foundation model for learning interpretable representations for context-specific transcriptional regulatory networks"
date:           2026-04-08 00:08:00 +0800
selected:       true
pub:            "<strong>Cell Genomics</strong>"
pub_date:       "2026"
abstract: >-
  Gene expression is shaped by transcriptional regulatory networks (TRNs), where transcription regulators interact within regulatory elements in a context-specific manner. Deciphering context-specific TRNs has long been constrained by the severe sparsity of cell-type-specific chromatin immunoprecipitation sequencing (ChIP-seq) profiles. Here, we present ChromBERT, a foundation model pre-trained on large-scale human ChIP-seq datasets covering ∼1,000 transcription regulators. ChromBERT learns the genome-wide syntax of regulatory cooperation and generates interpretable TRN representations. After prompt-enhanced fine-tuning, it outperforms existing methods for imputing unseen cistromes. Moreover, lightweight fine-tuning on cell-type-specific downstream tasks adapts the TRN representations to capture regulatory effects and dynamics within any given cellular context. The resulting context-specific representations can then be interpreted to infer regulatory roles of transcription regulators underlying these cell-type-specific regulatory outcomes without requiring additional ChIP-seq experiments. By overcoming the limitations of sparse transcription regulator data, ChromBERT significantly enhances our ability to model and interpret transcriptional regulation across a wide range of biological contexts.
cover:          /assets/images/covers/CellGenomics-2026.png
authors:
- <strong>Yu Z*</strong>
- Yang D*
- Chen Q*
- Zhang Y*
- Li Z
- Wang Y
- Wang C
- Zhang Y
links:
  Paper: https://www.cell.com/cell-genomics/fulltext/S2666-979X(25)00386-6
  Code: https://github.com/TongjiZhanglab/ChromBERT
---