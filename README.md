# DeepFrag-K: Deep learning methods to directly classify any protein into one of the well-known folds.

Run :
1-Put the target protein fasta sequence in 'fasta.fa' file. the fasta sequence must be on the following format :
 >d1a4pa_
 psqmehametmmftfhkfagdkgyltkedlrvlmekefpgflenqkdplavdkimkdldqcrdgkvgfqsffsliagltiacndyfvvhmkq
2- on the framework main directory using command line 'python deepfrag.py fasta.fa' to run the deepfragk prediector.

Output :
- Fold
A.39
- FASTA
PSQMEHAMETMMFTFHKFAGDKGYLTKEDLRVLMEKEFPGFLENQKDPLAVDKIMKDLDQCRDGKVGFQSFFSLIAGLTIACNDYFVVHMKQ
- FRAGMENTS FREQUANCY
10,4,5,10,8,4,1,8,7,11,0,3,1,6,6,2,4,4,11,8,8,3,0,1,3,1,8,9,25,2,7,5,4,10,16,12,1,29,6,4,7,2,10,7,5,0,7,9,3,7,2,11,1,9,5,4,9,8,3,9  ,0,2,1,7,7,5,9,2,7,5,8,3,5,6,2,3,5,6,0,8,7,2,7,15,0,28,9,0,1,13,9,4,16,5,8,5,4,3,22,11

Required Software Installation :
Python2.6
MongoDB
ubuntu server 18.01 LTS


Minimum Machine specx :
200 GB RAM
MultiCore Processor (Tested on 40 Cores).


Python Packages Dependancies :
pymongo
sklearn 2.x.x
pywt
tensorflow
keras
shutil
numpy
pprint


Database:
due to the size of the database, we provide a download link on request. please contact welhefna@odu.edu to provide the database access link.


Directories and Files:
|
|---fasta, fasta sequence processing, fasta sequence reader.
|---pssm, position specific scoring matrix reader.
|---vi, features calculations and scripts.
|---deepfrag.py, main program.
|---model.py, model reader and utilities.
|---README.txt, description of framework.
