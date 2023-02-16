# KEGG.db

# remotes::install_github("YuLab-SMU/createKEGGdb")
library(createKEGGdb)

# https://rdrr.io/github/GuangchuangYu/clusterProfiler/src/R/enrichKEGG.R
species <-c("hsa", "mmu", "rno")
create_kegg_db(species)
install.packages("./KEGG.db_1.0.tar.gz", repos=NULL)
