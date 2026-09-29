# Library demo run guide

## Prerequisites

- Python 3.9 or newer
- JDK 17 or newer, with `java` and `javac` available on `PATH`
- A local clone of this repository

The demo has no third-party dependencies. From the repository root, run:

```text
python3 run.py demo
```

The runner compiles the Java library in a temporary directory and starts a short
library-loan demonstration. It prints the borrowing policy, a loan receipt, an
overdue-fee example, and catalog search results.
