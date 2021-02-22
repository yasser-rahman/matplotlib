# Data Measurements Levels

The Four Levels of Measurement In order to choose an appropriate plot type or method of analysis for your data, you need to understand the types of data you have. One common method divides the data into four levels of measurement:

Qualitative or categorical types \(non-numeric types\) 1. Nominal data: pure labels without inherent order \(no label is intrinsically greater or less than any other\) 2. Ordinal data: labels with an intrinsic order or ranking \(comparison operations can be made between values, but the magnitude of differences are not be well-defined\) Quantitative or numeric types 3. Interval data: numeric values where absolute differences are meaningful \(addition and subtraction operations can be made\) 4. Ratio data: numeric values where relative differences are meaningful \(multiplication and division operations can be made\) All quantitative-type variables also come in one of two varieties: discrete and continuous.

Discrete quantitative variables can only take on a specific set values at some maximum level of precision. Continuous quantitative variables can \(hypothetically\) take on values to any level of precision. Distinguishing between continuous and discrete can be a little tricky – a rule of thumb is if there are few levels, and values can't be subdivided into further units, then it's discrete. Otherwise, it's continuous. If you have a scale that can only take natural number values between 1 and 5, that's discrete. A quantity that can be measured to two digits, e.g. 2.72, is best characterized as continuous, since we might hypothetically be able to measure to even more digits, e.g. 2.718. A tricky case like test scores measured between 0 and 100 can only be divided down to single integers, making it initially seem discrete. But since there are so many values, such a feature is usually considered as continuous.

When exploring your data, the most important thing to consider first is whether your data is qualitative or quantitative. In later lessons, you will see how this distinction impacts your choice of plots.

Likert Scale One form of data you might encounter is response data to a Likert scale like the ones below.

5-point Likert scale This Likert scale, which happens to be graphical, has five points, allowing for neutrality \(source: surveygizmo\)

Six-point Likert scale This Likert scale has six points, not allowing for neutrality \(source: fieldboom\)

What level of measurement should you consider for this kind of data? Technically, responses on these kinds of questions should be considered ordinal in nature. There is a clear order in response values, but it may not be the case that the differences between consecutive levels are consistent in size. The criteria to move between Strongly Disagree and Disagree might be different from the criteria between Agree and Strongly Agree. However, Likert data is often treated as interval to simplify analyses. If you have data like this, make sure you use exploratory data visualizations to make a good judgment on how your data should be treated later on in the analysis process.

