{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Goal of the hackaton\n",
    "\n",
  
    "Goal of this hackaton is to create a NER algo able to recognize aircraft occurences in a document.\n",
    "\n",
    "For instance: \n",
    "\n",
    "\"A Captain and First Officer of a **CE-560XL** reported...\"\n",
    "\n",
    "The main challenge is that there are no labels for the data. \n",
    "The onus is on you to create a dataset to train your algorithm. Your NER algo's performance will depend on the size of the supervized dataset you produce, as well as the learning strategy you choose.\n",
    "\n",
    "# Expected result:\n",
    "\n",
    "At the end of the day, the student will deliver a Flair SequenceTagger model that can be load through the following function: SequenceTagger.load('example_path/best_model.pt')\n",
    "\n",
    "The model will then be evaluated on my own validation dataset and the results will be compared to determine the winner of the hackaton. The validation dataset is made up of sentences that can be found in the data that is provided.\n",
    "\n",
    "# Data:\n",
    "\n",
    "The data provided is the ASR dataset: \"https://asrs.arc.nasa.gov\". \n",
    "\n",
    "You can access the data with the link provided below:\n",
    "\n",
    "https://drive.google.com/open?id=1fqhnETNivqsV73cV-DPQXIqWFiO12mhw\n",
    "\n",
    "Data is in pickle format, which can be used with pandas.read_pickle(\"path_to_pickle_file\") function.\n",
    "\n",
    "It is up to you to explore the data and decide on what to do with it in order to attain the expected results."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Good luck!"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.7.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 2
}
