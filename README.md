# Outlander Wordle

This is a clone project of the popular game for the TV series Outlander. Any length of word is accepted for more variability and a greater challenge. 

[**(ALMOST) Live here!**](http://google.com/)

## Build and run

Clone the repository and perform the following command line actions:

```cmd
$> cd react-wordle-main
$> npm install
$> npm run build
$> npm start
```

[Forked from great project here](https://github.com/cwackerfuss/react-wordle/)


### How do I change the length of solutions?

The original configuration is for five letter solutions and guesses, but it is flexible enough to handle other lengths.

To configure for variable lengths:

- Update the `WORDS` array in [src/constants/wordlist.ts](src/constants/wordlist.ts) to include words of any of length.
- Update the `VALID_GUESSES` array in [src/constants/validGuesses.ts](src/constants/validGuesses.ts) to include words of any of length.

Note that guesses are validated against both the length of the solution, and presence in VALID_GUESSES.


### How can I add usage tracking?
See source
