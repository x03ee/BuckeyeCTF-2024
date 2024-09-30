# Misc - Git Goo

![Challenge](https://github.com/x03ee/H7CTF-Writeups/blob/main/misc/had%20lunch/challenge.png)

## Solution

To solve this challenge, we utilized the following scripts:

1. **`gitdumper.sh`**: This script helps in extracting the contents of the target Git repository.
2. **`extractor.sh`**: After obtaining the repository, this script extracts the relevant files.

Upon running these scripts, we discovered a file named `flag.txt`. Opening this file revealed the flag.

![Flag Revealed](https://github.com/x03ee/H7CTF-Writeups/blob/main/misc/had%20lunch/flag.png)

![Flag Reveal 2](https://github.com/x03ee/H7CTF-Writeups/blob/main/misc/had%20lunch/flag.png)

## Final Flag

```
bctf{1_h4v3_c0mm17m3n7_i55u3s_cf39ab917a7dd092992a8f9b}
```
