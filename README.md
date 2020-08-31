# BPMN TCK

A test suite for BPMN workflow engines. Currently, available for [Zeebe](https://github.com/zeebe-io/zeebe).

The test cases are written as specification using the [bpmn-spec](https://github.com/saig0/bpmn-spec) test framework.

All test cases are stored in the folder: [/src/test/resources](/src/test/resources)

## Run the TCK

The test cases can be run as JUnit 5 tests in an IDE, or using the Maven command `mvn clean test`.

![BPMN-Spec JUnit test results](bpmn-spec-junit.png)