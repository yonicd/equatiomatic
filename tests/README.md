Tests and Coverage
================
02 August, 2020 19:48:25

  - [Coverage](#coverage)
  - [Unit Tests](#unit-tests)

This output is created by
[covrpage](https://github.com/yonicd/covrpage).

## Coverage

Coverage summary is created using the
[covr](https://github.com/r-lib/covr) package.

    ## ⚠️ Not All Tests Passed
    ##   Coverage statistics are approximations of the non-failing tests.
    ##   Use with caution
    ## 
    ##  For further investigation check in testthat summary tables.

| Object                                 | Coverage (%) |
| :------------------------------------- | :----------: |
| equatiomatic                           |    91.56     |
| [R/printer.R](../R/printer.R)          |     0.00     |
| [R/extract\_lhs.R](../R/extract_lhs.R) |    98.70     |
| [R/create\_eq.R](../R/create_eq.R)     |    100.00    |
| [R/extract\_eq.R](../R/extract_eq.R)   |    100.00    |
| [R/extract\_rhs.R](../R/extract_rhs.R) |    100.00    |
| [R/print.R](../R/print.R)              |    100.00    |
| [R/utils.R](../R/utils.R)              |    100.00    |

<br>

## Unit Tests

Unit Test summary is created using the
[testthat](https://github.com/r-lib/testthat) package.

| file                                                              |  n |  time | error | failed | skipped | warning | icon |
| :---------------------------------------------------------------- | -: | ----: | ----: | -----: | ------: | ------: | :--- |
| [test-basic.R](testthat/test-basic.R)                             |  2 | 0.061 |     0 |      2 |       0 |       0 | 🛑    |
| [test-clm.R](testthat/test-clm.R)                                 |  6 | 0.100 |     0 |      0 |       0 |       0 |      |
| [test-glm.R](testthat/test-glm.R)                                 |  8 | 0.122 |     0 |      0 |       0 |       0 |      |
| [test-lm.R](testthat/test-lm.R)                                   |  7 | 0.055 |     0 |      0 |       0 |       0 |      |
| [test-polr.R](testthat/test-polr.R)                               |  5 | 0.088 |     0 |      0 |       0 |       0 |      |
| [test-preview.R](testthat/test-preview.R)                         |  0 | 0.016 |     1 |      0 |       0 |       0 |      |
| [test-print.R](testthat/test-print.R)                             |  2 | 0.008 |     0 |      0 |       0 |       0 |      |
| [test-utils.R](testthat/test-utils.R)                             |  8 | 0.042 |     0 |      0 |       0 |       0 |      |
| [test-wrapping-formatting.R](testthat/test-wrapping-formatting.R) | 10 | 0.054 |     0 |      0 |       0 |       0 |      |

<details open>

<summary> Show Detailed Test Results </summary>

| file                                                                      | context                 | test                              | status | n |  time | icon |
| :------------------------------------------------------------------------ | :---------------------- | :-------------------------------- | :----- | -: | ----: | :--- |
| [test-basic.R](testthat/test-basic.R#L14)                                 | basic                   | extract: default                  | FAILED | 1 | 0.042 | 🛑    |
| [test-basic.R](testthat/test-basic.R#L18)                                 | basic                   | extract: all variables            | FAILED | 1 | 0.019 | 🛑    |
| [test-clm.R](testthat/test-clm.R#L46_L47)                                 | CLMs                    | Ordered models with clm work      | PASS   | 5 | 0.077 |      |
| [test-clm.R](testthat/test-clm.R#L79)                                     | CLMs                    | Unsupported CLMs create a message | PASS   | 1 | 0.023 |      |
| [test-glm.R](testthat/test-glm.R#L16_L17)                                 | GLMs                    | Logistic regression works         | PASS   | 1 | 0.018 |      |
| [test-glm.R](testthat/test-glm.R#L33_L34)                                 | GLMs                    | Probit regression works           | PASS   | 2 | 0.023 |      |
| [test-glm.R](testthat/test-glm.R#L49)                                     | GLMs                    | Unsupported GLMs create a message | PASS   | 1 | 0.012 |      |
| [test-glm.R](testthat/test-glm.R#L78_L79)                                 | GLMs                    | Distribution-based equations work | PASS   | 3 | 0.035 |      |
| [test-glm.R](testthat/test-glm.R#L107)                                    | GLMs                    | Weights work                      | PASS   | 1 | 0.034 |      |
| [test-lm.R](testthat/test-lm.R#L11_L12)                                   | Linear models           | Simple lm models work             | PASS   | 3 | 0.022 |      |
| [test-lm.R](testthat/test-lm.R#L32_L33)                                   | Linear models           | Interactions work                 | PASS   | 2 | 0.020 |      |
| [test-lm.R](testthat/test-lm.R#L48_L49)                                   | Linear models           | Custom Greek works                | PASS   | 2 | 0.013 |      |
| [test-polr.R](testthat/test-polr.R#L44_L45)                               | polr                    | Ordered logistic regression works | PASS   | 5 | 0.088 |      |
| [test-preview.R](testthat/test-preview.R#L11)                             | preview                 | preview: texPreview               | ERROR  | 0 | 0.016 |      |
| [test-print.R](testthat/test-print.R#L11_L12)                             | Printing                | Equation is printed correctly     | PASS   | 2 | 0.008 |      |
| [test-utils.R](testthat/test-utils.R#L9_L11)                              | Utility functions       | Strict mapply\_\* functions work  | PASS   | 8 | 0.042 |      |
| [test-wrapping-formatting.R](testthat/test-wrapping-formatting.R#L8_L9)   | Wrapping and formatting | Coefficient digits work correctly | PASS   | 2 | 0.013 |      |
| [test-wrapping-formatting.R](testthat/test-wrapping-formatting.R#L26_L27) | Wrapping and formatting | Wrapping works correctly          | PASS   | 8 | 0.041 |      |

| Failed | Warning | Skipped |
| :----- | :------ | :------ |
| 🛑      | ⚠️      | 🔶       |

</details>

<details>

<summary> Session Info </summary>

| Field    | Value                             |
| :------- | :-------------------------------- |
| Version  | R version 4.0.2 (2020-06-22)      |
| Platform | x86\_64-apple-darwin17.0 (64-bit) |
| Running  | macOS Catalina 10.15.6            |
| Language | en\_US                            |
| Timezone | America/New\_York                 |

| Package  | Version |
| :------- | :------ |
| testthat | 2.3.2   |
| covr     | 3.5.0   |
| covrpage | 0.0.70  |

</details>

<!--- Final Status : error/failed --->
