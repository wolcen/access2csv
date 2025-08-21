# access2csv

A tool to parse and convert Apache's (Combined Log Format) access.log to csv

## Usage

```console
usage: access2csv.py -i <PATH> -o <PATH> -e <PATH> [-m ERRMAX] [-h]

Convert Apache's (Combined Log Format) access.log to csv

required:
  -i, --input <PATH>   path to access.log file
  -o, --output <PATH>  path to output file
  -e, --error <PATH>   path to errors file

optional:
  -m, --errmax ERRMAX  maximum number of errors
  -h, --help           show this help message and exit
```

## Changes from sleepytariq/access2csv

- Allow X errors processing input
- Require error output file, capturing lineno/content for each parse error

## Requirements

Python 3.6 or later
