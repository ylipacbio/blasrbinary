Summary:

  blasr is an executable of BLASR compiled under Ubuntu 12.04, which 
  can align PacBio reads to reference genomes.

  This executable is provided for the convenience of users who want to
  try blasr in Unbutu (10.04 or 12.04) without compiling the source code. 
 
Instructions:

  # 1. Download blasr binary.
  > git clone git://github.com/ylipacbio/blasrbinary.git
  # 2. Change access mode of blasr binary.
  > cd blasrbinary
  > chmod +x blasr
  # 3. Try blasr.
  > ./blasr -h

Typical use cases:

  # Aligns reads from reads.fasta to reference sequences in ref.fasta,
  # and output in human-readable format.
  > blasr reads.fasta   ref.fasta -m 0 

  # Align PacBio reads from reads.bas.h5 to ecoli_K12 genome, and
  # output in SAM format.
  > blasr reads.bas.h5  ecoli_K12.fasta -sam


Citation:

  To cite BLASR, please use: Chaisson M.J., and Tesler G., Mapping
  single molecule sequencing reads using Basic Local Alignment with
  Successive Refinement (BLASR): Theory and Application, BMC
  Bioinformatics 2012, 13:238 .


Note:

  If this blasr executable does not work on your own Linux system, 
  please download blasr's source code at
     https://github.com/PacificBiosciences/blasr
  , and follow the instructions described at 
     https://github.com/PacificBiosciences/blasr/blob/master/README.txt
  .
