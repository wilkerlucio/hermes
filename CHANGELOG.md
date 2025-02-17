# Changes

This log documents significant changes for each release.

## [] - HEAD - not yet released

* New graph API using declarative approach permitting clients to ask for exactly what they need
* Expose fuzzy search in REST API.
* Restructure - separate library code from cli commands / server

## [0.6.2] - 2021-04-20

* Permit prefix search to run with one character or more, rather than minimum of three, for better autocompletion functionality.

## [0.6.1] - 2021-04-19

* Upgrade dependencies
* Temporarily bind to 0.0.0.0 pending more complete server configuration options

## [0.6.0] - 2021-03-31

* Support for unlimited results when used as a library, and when processing expressions
* Harmonise web service key names to use camel case and not mix in kebab-case.
* Expose library API call to get installed reference sets
* Expose support for 'Accept-Language' using BCP 47 language tags in REST server, with additional support for specific language reference set extension of form en-gb-x-XXXX where XXXX is preferred language refset.  
* Release information included in log files

## [0.5.0] - 2021-03-09

* Minor fixes

## [0.4.0] - 2021-03-08

* Major change to backend store with new custom serialization resulting in enormous speed-up and size benefits.
* UK dictionary of medicines and devices (dm+d) custom code extracted to [another repository](https://github.com/wardle/dmd) 
* Add support for transitive synonyms

## [0.3.0] - 2021-01-27

* Add special custom extension for UK dictionary of medicines and devices (dm+d) to bring in non-SNOMED BSA data
* SNOMED ECL (expression constraint language) support
* SNOMED CG (compositional grammar) support  
* Major improvements to server and backend. Unified terminology service abstracting underlying implementations.

## [0.2.0] - 2020-11-18

* Added search and autocompletion using Apache Lucene

## [0.1.0] - 2020-11-12

* Basic SNOMED service (store/retrieval/inference)

