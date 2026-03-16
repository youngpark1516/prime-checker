# prime-checker

A Python library for checking whether numbers are prime. Accuracy to be around 93.4% at 10 million tests, expected to increase with more tests.

## Structure
```text
prime-checker/
├── pyproject.toml
├── README.md
├── src/
│   └── prime_checker/
│       ├── __init__.py
│       └── core.py
└── tests/
    └── test_prime_checker.py
```

## Install

```bash
pip install -e .
```

## Usage

```python
from prime_checker import is_prime

print(is_prime(2))
print(is_prime(15))
```
