# Welcome to the Biodiversity Genomics course
## held for the first time at [Ikiam](https://www.ikiam.edu.ec), in Tena, Ecuador in July 2024
This course taught by Karin Näsvall, Nicol Rueda and Joana Meier from the [Wellcome Sanger Institute](https://www.sanger.ac.uk/group/meier-group/) is an adapted version of the [speciation genomics course](https://speciationgenomics.github.io/) by Mark Ravinet and Joana Meier. Here you will find all relevant course materials for the biodiversity genomics course, including all files we used during the course in case you want to redo anything at home.

Day 1:
- [Slides](slide_presentations/01_Welcome_BiodiversityGenomics_introduction.pdf) introducing biodiversity genomics and sequencing technologies
- [Slides](slide_presentations/02_Summary_reads-vcf.pdf) summarising the steps from getting raw Illumina reads, filtering, aligning them to a reference and calling variants and genotypes
- [Slides](slide_presentations/03_Raw_sequences_and_quality_control.pdf) introducing the structure of Illumina reads and fastq files
- [Slides](exercises/Connecting_to_the_Amazon_server.pdf) on logging on to the Amazon server by Carlo Pecoraro from [Physalia Courses](https://www.physalia-courses.org)
- [Exercise](exercises/01_RawReadsExploration_fastqc.md) on exploring Illumina reads and visualising the quality with fastqc which uses these [input files](input_files/raw_reads)
- [Slides](slide_presentations/04_fastqc_interpretation.pdf) on interpreting fastqc output of RAD data

Day 2:
- [Exercise](02_fastp_filtering_reads.md) on filtering Illumina reads with fastp which uses these [input files](input_files/raw_reads)
- [Slides](slide_presentations/06_Aligning_reads_to_reference.pdf) on aligning reads to a reference genome
- [Exercise](03_Mapping_to_a_reference_genome.md) to align Illumina paired-end reads to a reference genome with bwa-mem2
- [Slides](slide_presentations/07_Variant_and_genotype_calling.pdf) about variant and genotype calling

Day 3:
- [Exercise](exercises/04_variant_calling.md) on variant and genotype calling with bcftools.
- [Exercise](exercises/05_filtering_variants.md) on filtering vcf files.
- [Slides](slide_presentations/08_Ithomiini_introduction_PCA.pdf) introducing ithomiini butterflies and PCA
- [Exercise](exercises/06_pca.md) on PCA.
- [Exercise](exercises/07_iqtree.md) on making phylogenies with iqtree.

Day 4:
- [Slides](slide_presentations/09_Detecting_hybridisation_Dstats.pdf) on identifying introgression with D statistics
- [Exercise](exercises/08_Dstatistics.md) on Dstatistics to infer introgression using Dsuite
- [Slides](slide_presentations/10_Genome_scans.pdf) on genome scans
- [Exercise](exercises/09_genome_scan.md) on genome scans

Day 5:
- [Slides](slide_presentations/11_Comparative%20genomics.pdf) on comparative genomics
- [Exercise](exercises/Synteny.md) on macrosynteny
- [Slides](slide_presentations/12_Phylogenomics.pdf) on phylogenomics with BUSCO genes
- [Exercise](exercises/11_gene_trees.md) on phylogenomics with BUSCO genes
- [Slides](slide_presentations/13_Course_Summary.pdf) summarising the course and giving some suggestions for further learning

## Learning more
### Biodiversity Genomics Academy
Free to attend, fully online tutorials about genome assembly, curation and annotation, comparative genomics and more. The next session will be in October and all tutorials of last year are available on Youtube/GitPod:
https://thebgacademy.org

### Biodiversity Genomics Conference
28 October - 1 November: Online, free conference on biodiversity genomics across all time zones: 
https://www.biodiversitygenomicsconference.org

### Physalia courses
[Physalia courses](https://www.physalia-courses.org/) offers lots of great courses on genomics, bioinformatics, and related fields. The [Speciation Genomics](https://speciationgenomics.github.io/) course was a course taught via Physalia.

### Speciation genomics course website
https://speciationgenomics.github.io/ contains many more tutorials, including topics not covered here, such as demographic modeling, haplotype-based tests for selection, advanced unix and R tutorials, simulating data with SliM, etc.

##
## Publications we recommend:

### Introduction to Unix
- Introduction to the Unix Command Line [Dowling, et al., 2019](Papers/Introduction_unix_command-may2019.pdf)
- Unix and Perl Primer for Biologists [Bradnam, et al 2016](Unix_Perl.pdf)

### Reviews on biodiversity genomics:
- How genomics can help biodiversity conservation [Theissinger et al. 2023](Papers/Theissinger_et_al-2023_Genomics_Conservation.pdf)
- Genomics and the origin of species [Seehausen et al. 2015](Papers/Seehausen_et_al-15-NatRevGenet.pdf)

### Publications related to the examples in the course:
- Genomics of Neotropical biodiversity indicators: two butterfly radiations with rampant chromosomal rearrangements and hybridisation [van der Heijden et al. 2024](Papers/vanDerHeijden_et_al-2025-Biorxiv.pdf)
- Genomic evidence reveals three W-autosome fusions in Heliconius butterflies [Rueda et al. 2024](Papers/Rueda_et_al-24-PlosGenetics.pdf)

### Papers or manuals for some of the tools mentioned in this course:
- Arima-HiC Mapping Pipeline [Arima Genomics](Papers/Arima_Mapping_UserGuide.pdf)
- Tutorial on ASTRAL [Mirarab, et al](Papers/Species_tree_Astral-tutorial.pdf)
- DensiTree Manual: Making sense of sets of trees [Bouckaert, et_al 2014](Papers/DensiTree_Manual.v2.2.pdf)
- Local PCA Shows How the Effect of Population Structure Differs Along the Genome [Li, et al., 2019](Papers/Li_2019_Local_PCA_Shows_How_the_Effect_of_Population_lostruct.pdf)
- The Sequence Alignment/Map format and SAMtools [Li, et al., 2019](Papers/Li_H_2009_The_Sequence_Alignment_Map_format_and_SAMtools.pdf)
- Dsuite - Fast D-statistics and related admixture evidence from VCF files [Malinsky, et al., 2020](Papers/Malinsky_2020_Dsuite.pdf)
- Sequence Alignment Map Format Specification [SAM BAM group](Papers/Sequence_Alignment_Map_Format_Specification.pdf)
- Quality Scores for Next-Generation Sequencing [Illumina](Papers/technote_Q-Scores.pdf)
- Accurate, scalable and integrative haplotype estimation (SHAPEIT4) [Delaneau, et al., 2019](Papers/Accurate_scalable_and_integrative_haplotype_estimation.pdf)
- WhatsHap: Weighted Haplotype Assembly for Future-Generation Sequencing Reads [Patterson, et al., 2015](Papers/WhatsHap.pdf)
- Modern technologies and algorithms for scaffolding assembled genomes [Ghurye, et al., 2019](Papers/Modern_technologies_and_algorithms_for_scaffolding_assembled_genomes.pdf)

### Reviews on phylogenomics
- Phylogenomics and the reconstruction of the tree of life [Delsuc, et al., 2005](Papers/Delsuc_F.etal.2005_PHYLOGENOMICS.pdf)
- Phylogenetic tree building in the genomic age [Kapli, et al., 2020](Papers/Kapli_phylogenomics_in_genomic_era.pdf)
- Genetic Terminology [Elston, et al 2012](Paper/Elston_2012_Genetic_Terminology.pdf)
- Phylogenomics reveals the evolutionary timing and pattern of butterflies and moths [Kawahara, et al 2019](Papers/kawahara_etal-2019_phylogenomic_reveals_evolutionary_timing_pattern_butterflies_and_moths)
- A method for genome-wide genealogy estimation for thousands of samples [Speidel, et al., 2019](Papers/A_method_for_genome_wide_genealogy.pdf)
- BUSCO Update: Novel and Streamlined Workflows along with Broader and Deeper Phylogenetic Coverage for Scoring of Eukaryotic, Prokaryotic, and Viral Genomes [Manni, et al., 2021](Papers/BUSCO_Update_Novel_and_Streamlined_Workflows.pdf)

### Reviews on speciation
- What does Drosophila genetics tell us about speciation? [Mallet, J., 2006](Papers/Mallet,J_2006_speciation.pdf)
- Defining the speciation continuum. [Stankowski, et al., 2021](Papers/Stankowski_etal,2021_Defining_the_speactiation_continuum.pdf)

### Reviews or examples about introgression
- Phylogenomic approaches to detecting and characterizing introgression [Hibbins, et al., 2022](Papers/Hibbins_M._2021._Phylogenomic_approaches_to_detecting_and_characterizing)
- Evaluating the Use of ABBA–BABA Statistics to Locate Introgressed Loci [Martin, et al., 2015](Papers/Martin_etal_2015_Evaluating_Use_ABBA–BABA_Statistics.pdf)
- The genetic consequences of hybridization [Moran, et al., 2021](Papers/The_genomic_consequences_of_hybridization.pdf)
- How reticulated are species? [Mallet, et al., 2015](Mallet_How_reticulated_are_species)

### Reviews or examples on chromosome evolution
- Chromosomal rearrangements and speciation. [Rieseberg, et al., 2021](Papers/Rieseberg,etal.,_2001_Chromosomal_rearrangement_and_speciation.pdf)
- Chromosome evolution [Ingo Schubert, 2019](Papers/Chromosome_evolution.pdf)
- The Impact of Chromosomal Rearrangements in Speciation: From Micro- to Macroevolution [Lucek, et al., 2023](Papers/The_Impact_of_Chromosomal_Rearrangements_Speciation.pdf)

### Review on next-generation sequencies technologies
- Next-Generation Sequencing Technology: Current Trends and Advancements [Satam, et al., 2023](Papers/Satam_et_al_2024_Next_generation_sequencing.pdf)

### Population genomic diversity and divergence statistics
- Patterns of Z chromosome divergence among Heliconius species highlight the importance of historical demography [Van Belleghem, et al., 2017](Van_Belleghem_2018_Patterns_of_z_chromosome.pdf)
- Complex modular architecture around a simple toolkit of wing pattern genes [Van Belleghem, 2018](VanBelleghem_2017_Complex_modular_architecture_around_simple_toolkit_of_wing_pattern_genes.pdf)
