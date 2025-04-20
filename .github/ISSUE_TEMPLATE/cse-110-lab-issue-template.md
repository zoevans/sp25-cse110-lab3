---
name: CSE 110 Lab issue template
about: The purpose of this issue template is to track and breakdown all of this week's
  lab tasks.
title: ''
labels: ''
assignees: zoevans

---

# Task:
>Insert task title here!

- type: textarea
  id: title
  attributes:
    label: title
    description: "Insert a task title that is a clear title of the task."
    value: Insert task title here!
    render:
  validations:
    required: true

### Description:
>Insert a task description here!
>
- type: textarea
  id: description
  attributes:
    label: description
    description: "Insert a task description that is a clear descriptor of the task."
    value: Insert task description here!
    render:
  validations:
    required: true
