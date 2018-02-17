---
---

{% include header.html %}

# About the Cabbage Looper Database
This database provides access to the cabbage looper (*Trichoplusia ni*) genome assembly and annotation. [![Github All Releases](https://img.shields.io/github/downloads/weng-lab/cabbagelooper/total.svg?style=flat-square)](https://github.com/weng-lab/cabbagelooper)
## Genome assemblies
The latest cabbage looper genome assembly (tn1) contains 1,031 scaffolds spanning 368.2 Mb. The scaffold N50 is 14.2 Mb, with >90% of the bases in 28 chromosome-length scaffolds. Contig N50 is 621.9 kb. 

[Scaffolds](https://github.com/weng-lab/cabbagelooper/releases/download/v1.0-scaffolds-and-contigs/tn1.scaffolds.fasta.gz) and [Contigs](https://github.com/weng-lab/cabbagelooper/releases/download/v1.0-scaffolds-and-contigs/tn1.contigs.fasta.gz)

## Annotation resource
The latest official gene set (OGS v1.0) is based on the tn1 genome assemnbly and contains 14,034 protein-coding genes.

[OGS v1.0 GFF](https://github.com/weng-lab/cabbagelooper/releases/download/v1-annotation/tn1.genes.gff.gz)

[OGS v1.0 gene annotation](https://github.com/weng-lab/cabbagelooper/releases/download/v1-annotation/tn1.annotation.txt.gz)

[OGS v1.0 transcripts](https://github.com/weng-lab/cabbagelooper/releases/download/v1-annotation/tn1.transcripts.fasta.gz)

[OGS v1.0 peptides](https://github.com/weng-lab/cabbagelooper/releases/download/v1-annotation/tn1.pep.fasta.gz)

[RepeatMasker output](https://github.com/weng-lab/cabbagelooper/releases/download/v1.0-scaffolds-and-contigs/tn1.rmsk_out.gz)

[Repeat Consensus sequences](https://github.com/weng-lab/cabbagelooper/releases/download/v1.0-scaffolds-and-contigs/tn1.repeatmodeler.fasta.gz)

[Genomic variants called using sequencing data from Hi5 cells](https://github.com/weng-lab/cabbagelooper/releases/download/v1-annotation/tn1.Hi5.tetraploid.vcf.gz)
<!---[TODO microRNA annotation]--->

## piRNA clusters
[piRNA clusters](https://github.com/weng-lab/cabbagelooper/releases/download/v1-annotation/tn1.piRNAclusters.tar.gz)

## Visualization

[UCSC genome browser](http://genome.ucsc.edu/cgi-bin/hgTracks?hubUrl=http://zlab-trackhub.umassmed.edu/yfu/insects/hub.txt&db=hub_129615_cl_v0.8.2)

If you prefer loading the track hub yourself, it is available [here](http://zlab-trackhub.umassmed.edu/yfu/insects/hub.txt)

## BLAST

Search *T. ni* nucleotides using a nucleotide query: [blastn](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE_TYPE=BlastSearch&USER_FORMAT_DEFAULTS=on&SET_SAVED_SEARCH=true&PAGE=Nucleotides&PROGRAM=blastn&GAPCOSTS=5%202&MATCH_SCORES=2,-3&DATABASE=Whole_Genome_Shotgun_contigs&BLAST_PROGRAMS=blastn&MAX_NUM_SEQ=100&SHORT_QUERY_ADJUST=on&EXPECT=10&WORD_SIZE=7&REPEATS=repeat_9606&TEMPLATE_TYPE=0&TEMPLATE_LENGTH=0&FILTER=L&FILTER=m&EQ_MENU=336361%3A%20Trichoplusia%20ni%20isolate%3Aovarian%20cell%20line%20Hi5&DB_GROUP=WGSBioProj&PROG_DEFAULTS=on&SHOW_OVERVIEW=true&SHOW_LINKOUT=true&ALIGNMENT_VIEW=Pairwise&MASK_CHAR=2&MASK_COLOR=1&GET_SEQUENCE=true&NEW_VIEW=false&NCBI_GI=false&NUM_OVERVIEW=100&DESCRIPTIONS=100&ALIGNMENTS=100&FORMAT_OBJECT=Alignment&FORMAT_TYPE=HTML&SHOW_CDS_FEATURE=false)

Search translated *T. ni* nucleotides using a protein query: [tblastn](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE_TYPE=BlastSearch&USER_FORMAT_DEFAULTS=on&SET_SAVED_SEARCH=true&PAGE=Translations&PROGRAM=tblastn&GAPCOSTS=11%201&DATABASE=Whole_Genome_Shotgun_contigs&MAX_NUM_SEQ=100&EXPECT=10&WORD_SIZE=6&MATRIX_NAME=BLOSUM62&COMPOSITION_BASED_STATISTICS=2&FILTER=L&EQ_MENU=336361%3A%20Trichoplusia%20ni%20isolate%3Aovarian%20cell%20line%20Hi5&DB_GROUP=WGSBioProj&BLAST_PROGRAMS=tblastn&SHOW_OVERVIEW=true&SHOW_LINKOUT=true&ALIGNMENT_VIEW=Pairwise&MASK_CHAR=2&MASK_COLOR=1&GET_SEQUENCE=true&NEW_VIEW=true&NCBI_GI=false&NUM_OVERVIEW=100&DESCRIPTIONS=100&ALIGNMENTS=100&FORMAT_OBJECT=Alignment&FORMAT_TYPE=HTML&SHOW_CDS_FEATURE=false)

Search translated *T. ni* nucleotides using a translated nucleotide query: [tblastx](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE_TYPE=BlastSearch&USER_FORMAT_DEFAULTS=on&SET_SAVED_SEARCH=true&PAGE=Translations&PROGRAM=tblastx&GAPCOSTS=11%201&DATABASE=Whole_Genome_Shotgun_contigs&MAX_NUM_SEQ=100&EXPECT=10&WORD_SIZE=3&MATRIX_NAME=BLOSUM62&COMPOSITION_BASED_STATISTICS=0&FILTER=L&EQ_MENU=336361%3A%20Trichoplusia%20ni%20isolate%3Aovarian%20cell%20line%20Hi5&DB_GROUP=WGSBioProj&BLAST_PROGRAMS=tblastx&SHOW_OVERVIEW=true&SHOW_LINKOUT=true&ALIGNMENT_VIEW=Pairwise&MASK_CHAR=2&MASK_COLOR=1&GET_SEQUENCE=true&NEW_VIEW=true&NCBI_GI=false&NUM_OVERVIEW=100&DESCRIPTIONS=100&ALIGNMENTS=100&FORMAT_OBJECT=Alignment&FORMAT_TYPE=HTML&SHOW_CDS_FEATURE=false)

## Raw data
This Whole Genome Shotgun project has been deposited at DDBJ/ENA/GenBank
under the accession [NKQN00000000](https://www.ncbi.nlm.nih.gov/nuccore/NKQN00000000).
Sequencing data are available through the NCBI Sequence Read Archive under the accession number [PRJNA336361](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA336361).

[Figure source data](https://github.com/weng-lab/cabbagelooper/releases/download/v1-source-data/figure_source_data.zip)


## Related databases
[NCBI](http://www.ncbi.nlm.nih.gov/)

[Ensembl](http://www.ensembl.org/index.html)

[SilkDB](http://silkworm.genomics.org.cn/)

[KAIKObase](http://sgp.dna.affrc.go.jp/KAIKObase/)

[DBM-DB](http://iae.fafu.edu.cn/DBM/index.php)

[FlyBase](http://flybase.org/)

[VectorBase](https://www.vectorbase.org/)

## Contact us
*Trichoplusia ni* (Trichoplusia.ni {at} gmail.com)

Yu Fu (Yu.Fu {at} umassmed.edu)
