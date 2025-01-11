Answer 1: No, SNS does not guarantee exactly-once delivery.
Answer 2: A Dead-letter Queue is used to handle messages that cannot be successfully processed by their intended destination after a configured number of retries.
Answer 3: 1）Create an SNS Topic
          2）Configure CloudWatch Alarms for the DLQ
          3）Set SNS Topic as Alarm Action
