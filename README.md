# Calculating-onset-entropy

This Python script will calculate the onset entropy for the phoneme --> letter direction, though one could easily modify it to calculate the letter-->phoneme entropy by swapping "letter" and "phoneme". 

The Orth.txt input file should consist of a list of written words in one's orthography of choice, and the Phon.txt file a list of transcribed spoken word forms (1 phoneme = 1 character), with the words in the same order as in the Orth.txt file. 

The way onset entropy is calculated is based on a publication from another lab:

Borgwaldt, S., Hellwig, F., & de Groot, A. (2004). Word-initial entropy in five languages: Letter to sound, and sound to letter. Written Language & Literacy, 7(2), 165-184. 
