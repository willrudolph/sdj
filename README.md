# SDJ 
## Self-Described JSON

## What it is:
SDJ is a library that reads and creates ".sdj" files which are a subset of standard json/text files. 
Unlike standard JSON, sdj files internalize self-description of the data which it contains.
This allows for a extremely flexable data format that can describe, store, retrieve, and transmit nearly any type of data using the standard JSON format.
This library transforms between immutable and mutable forms of sdj javascript/typescript objects.


# Licensing
SDJ library is provided under the [LGPLv3](https://www.gnu.org/licenses/lgpl-3.0.en.html) copy left license.
This is due to the core nature of this library as starting point for all of the other projects built upon it.

Do review the licensing if you have questions; most simply put, if you use this library and modify it for
proprietary uses, you must publicly provide the modified code. All derivative OSS or proprietary code that does
not modify this library does not have to be public. If the library is modified only the library revisions would need to be OSS/public. 

Improvements to the core SDJ Library should be a responsibility and benefit to the people that participate in its growth.

Ideally only SDJ language implementations (JS, Java*, Python*) should provided under this license.


### What it Does:

- TypeScript/JavaScript implementation of SJK JSON schema
- Creates JS data objects and provides TS data reference for data elements
- Allows easy hydration/de-hydration between data/class/immutable states
- Provides easily accessible JS data objects and structure
- Verifies and throws errors with JSON files based on the SDJ description rules
- Maintains Agnostic to contained content, templating, other libraries, and code


### What is Does NOT (or should not):

- Allow dynamic load of code / command statements 
  - {String checking hardened to disallow / limit / control basic issues}
- Store or maintain html templating information or implementation info
- Store or maintain CSS information or stylesheets
- Store or maintain non-JSON data
- Store or maintain data outside of the SDJ JSON format/schema
  - You could stuff something in there, but don't.
- Implement routing, creation, instantiation routines for specific libraries

### Goals

- Maintain the SDJ (.sdj) file format and JSON schema
- Centralize controls/development/code implementation for SDJ TS/JavaScript
- Keep the library small and maintainable with specialized function
- Minimize size of active library

