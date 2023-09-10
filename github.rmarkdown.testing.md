Simplified CDM and IRT:  
Parameter Comparison
================
July 14, 2022

- <a href="#1-simulation-study-design"
  id="toc-1-simulation-study-design">1. Simulation Study Design</a>
- <a href="#2-rasch-model-parameter-estimation"
  id="toc-2-rasch-model-parameter-estimation">2. Rasch Model Parameter
  Estimation</a>
- <a href="#3-parameter-comparison" id="toc-3-parameter-comparison">3.
  Parameter Comparison</a>
  - <a href="#31-dina-vs-rasch" id="toc-31-dina-vs-rasch">3.1. DINA
    vs. Rasch</a>
  - <a href="#32-nida-vs-rasch" id="toc-32-nida-vs-rasch">3.2. NIDA
    vs. Rasch</a>
- <a href="#4-discussion" id="toc-4-discussion">4. Discussion</a>

<style type="text/css">
#TOC 
.list-group-item.active, .list-group-item.active:focus, .list-group-item.active:hover {
    background-color: #00356B;
    border-color: #00356B;
}

caption {
    font-weight: bold;
    font-size: 1.0em;
} 

.table-hover > tbody > tr:hover { 
  background-color: #f1f1f1;
}

</style>
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABnMAAAOFCAIAAAA+t4BrAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAFeoSURBVHhe7d19rNXVnS/+6iitPzg83E6Zhodb/aPDU5vajgqYmfRIhcM/iqVAbiJGFJpcSMRyJvE08SRAAsnFpKCYwE0KilGTCSAj+g8HKNJMIx6xlmbKU+cP7XAO6dDrBc6BtEVHfkv3Gi5VwcM6Z++9vt/9eoXQ9dnQlrP3d6/9Xe+9Hq67ePHiFwAAAACAa3R9/E8AAAAA4FpI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAAAFJI1gAAAAAghWQNAAAA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WQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAFJI1AAAAAEghWQMAAACAa/eFL/z/C3FqQwrQnxQAAAAASUVORK5CYII=" alt="logo" style="position:absolute; top:0; right:0; padding:10px;" width="220px" heigth="220px"/>

<br>

# 1. Simulation Study Design

<br> The purpose of this simulation study is to explore the
relationships between parameters estimated from cognitive diagnostic
models (CDM) and ones from item response theory models (IRT). Among the
CDMs, this study focused on DINA and NIDA models with items that involve
one single skill per item (see the Q matrix below). We generated learner
response data using the following true values. The simulated data by
DINA and NIDA were analyzed by one of the IRT models, Rasch, to estimate
item difficulty and learner skill values.  
<br>

<div
style="border: 1px solid #ddd; padding: 0px; overflow-y: scroll; height:600px; overflow-x: scroll; width:100%; ">

<table class=" lightable-classic" style="font-family: &quot;Arial Narrow&quot;, &quot;Source Sans Pro&quot;, sans-serif; margin-left: auto; margin-right: auto;">
<caption>

Learner Skill Mastery

200 learners x 5 skills
</caption>
<thead>
<tr>
<th style="text-align:right;position: sticky; top:0; background-color: #FFFFFF;">
Learner
</th>
<th style="text-align:right;position: sticky; top:0; background-color: #FFFFFF;">
Skill1
</th>
<th style="text-align:right;position: sticky; top:0; background-color: #FFFFFF;">
Skill2
</th>
<th style="text-align:right;position: sticky; top:0; background-color: #FFFFFF;">
Skill3
</th>
<th style="text-align:right;position: sticky; top:0; background-color: #FFFFFF;">
Skill4
</th>
<th style="text-align:right;position: sticky; top:0; background-color: #FFFFFF;">
Skill5
</th>
<th style="text-align:right;position: sticky; top:0; background-color: #FFFFFF;">
Total \# of Skills
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
2
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
3
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
4
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
5
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
6
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
7
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
8
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
9
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
10
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:right;">
11
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
12
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
13
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
14
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
15
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
16
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
17
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
18
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
19
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
20
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
21
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
22
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
23
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
24
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
25
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
26
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
27
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
28
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
29
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
30
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
31
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
32
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
33
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
34
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
35
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
36
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
37
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
38
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
39
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
40
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
41
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
42
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
43
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
44
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
45
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
46
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
47
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
48
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
49
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
50
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:right;">
51
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
52
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
53
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
54
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
55
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
56
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
57
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
58
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:right;">
59
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
60
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
61
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
62
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
63
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
64
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
65
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
66
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
67
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
68
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
69
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
70
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
71
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
72
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
73
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
74
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
75
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
76
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
77
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
78
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
79
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
80
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
81
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:right;">
82
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
83
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
84
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
85
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
86
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
87
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
88
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
89
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
90
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
91
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
92
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
93
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
94
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
95
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
96
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
97
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
98
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
99
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
100
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
101
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
102
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
103
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
104
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
105
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:right;">
106
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
107
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
108
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
109
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
110
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
111
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
112
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
113
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
114
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
115
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
116
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
117
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
118
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
119
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
120
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
121
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
122
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
123
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
124
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
125
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
126
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
127
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:right;">
128
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
129
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
130
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
131
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
132
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
133
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
134
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
135
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
136
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
137
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
138
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:right;">
139
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
140
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
141
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:right;">
142
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
143
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
144
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
145
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
146
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
147
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
148
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
149
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
150
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
151
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
152
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
153
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
154
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
155
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
156
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
157
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
158
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
159
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
160
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
161
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
162
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
163
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
164
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
165
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
166
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
167
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
168
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:right;">
169
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
170
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
171
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
5
</td>
</tr>
<tr>
<td style="text-align:right;">
172
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
173
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
174
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
175
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
176
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
177
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
178
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
179
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
180
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
181
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
182
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
183
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
184
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
185
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
186
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
187
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
188
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
189
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
190
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
191
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
192
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
193
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
194
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
195
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
196
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
197
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
3
</td>
</tr>
<tr>
<td style="text-align:right;">
198
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
<tr>
<td style="text-align:right;">
199
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
4
</td>
</tr>
<tr>
<td style="text-align:right;">
200
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
2
</td>
</tr>
</tbody>
</table>

</div>

<br>

<table class=" lightable-classic" style="font-family: &quot;Arial Narrow&quot;, &quot;Source Sans Pro&quot;, sans-serif; margin-left: auto; margin-right: auto;">
<caption>

Q Matrix (Item Skill Mapping)

30 items x 5 skills
</caption>
<thead>
<tr>
<th style="text-align:right;">
Item
</th>
<th style="text-align:right;">
Skill1
</th>
<th style="text-align:right;">
Skill2
</th>
<th style="text-align:right;">
Skill3
</th>
<th style="text-align:right;">
Skill4
</th>
<th style="text-align:right;">
Skill5
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
2
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
3
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
4
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
5
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
6
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
7
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
8
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
9
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
10
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
11
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
12
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
13
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
14
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
15
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
16
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
17
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
18
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
19
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
20
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
21
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
22
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
23
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
24
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
25
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
26
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
</tr>
<tr>
<td style="text-align:right;">
27
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
28
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
29
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
</tr>
<tr>
<td style="text-align:right;">
30
</td>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
<td style="text-align:right;">
0
</td>
</tr>
</tbody>
</table>

<br>

<table class=" lightable-classic" style="font-family: &quot;Arial Narrow&quot;, &quot;Source Sans Pro&quot;, sans-serif; margin-left: auto; margin-right: auto;">
<caption>

DINA Item Parameters

30 items x 2 parameters
</caption>
<thead>
<tr>
<th style="text-align:right;">
Item
</th>
<th style="text-align:right;">
Hit (1 - Slip)
</th>
<th style="text-align:right;">
Guess
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:right;">
1
</td>
<td style="text-align:right;">
0.6402064
</td>
<td style="text-align:right;">
0.0663373
</td>
</tr>
<tr>
<td style="text-align:right;">
2
</td>
<td style="text-align:right;">
0.7664291
</td>
<td style="text-align:right;">
0.1487147
</td>
</tr>
<tr>
<td style="text-align:right;">
3
</td>
<td style="text-align:right;">
0.8615828
</td>
<td style="text-align:right;">
0.0857883
</td>
</tr>
<tr>
<td style="text-align:right;">
4
</td>
<td style="text-align:right;">
0.6315809
</td>
<td style="text-align:right;">
0.2794831
</td>
</tr>
<tr>
<td style="text-align:right;">
5
</td>
<td style="text-align:right;">
0.6475758
</td>
<td style="text-align:right;">
0.2280644
</td>
</tr>
<tr>
<td style="text-align:right;">
6
</td>
<td style="text-align:right;">
0.7611137
</td>
<td style="text-align:right;">
0.2544553
</td>
</tr>
<tr>
<td style="text-align:right;">
7
</td>
<td style="text-align:right;">
0.7280119
</td>
<td style="text-align:right;">
0.1616461
</td>
</tr>
<tr>
<td style="text-align:right;">
8
</td>
<td style="text-align:right;">
0.6234309
</td>
<td style="text-align:right;">
0.0553341
</td>
</tr>
<tr>
<td style="text-align:right;">
9
</td>
<td style="text-align:right;">
0.8232062
</td>
<td style="text-align:right;">
0.1940295
</td>
</tr>
<tr>
<td style="text-align:right;">
10
</td>
<td style="text-align:right;">
0.6850177
</td>
<td style="text-align:right;">
0.2268624
</td>
</tr>
<tr>
<td style="text-align:right;">
11
</td>
<td style="text-align:right;">
0.9187429
</td>
<td style="text-align:right;">
0.1327583
</td>
</tr>
<tr>
<td style="text-align:right;">
12
</td>
<td style="text-align:right;">
0.8295276
</td>
<td style="text-align:right;">
0.2293021
</td>
</tr>
<tr>
<td style="text-align:right;">
13
</td>
<td style="text-align:right;">
0.8530992
</td>
<td style="text-align:right;">
0.0538474
</td>
</tr>
<tr>
<td style="text-align:right;">
14
</td>
<td style="text-align:right;">
0.6248707
</td>
<td style="text-align:right;">
0.0769292
</td>
</tr>
<tr>
<td style="text-align:right;">
15
</td>
<td style="text-align:right;">
0.8828779
</td>
<td style="text-align:right;">
0.0924592
</td>
</tr>
<tr>
<td style="text-align:right;">
16
</td>
<td style="text-align:right;">
0.6346501
</td>
<td style="text-align:right;">
0.2723798
</td>
</tr>
<tr>
<td style="text-align:right;">
17
</td>
<td style="text-align:right;">
0.8044818
</td>
<td style="text-align:right;">
0.1538909
</td>
</tr>
<tr>
<td style="text-align:right;">
18
</td>
<td style="text-align:right;">
0.8455635
</td>
<td style="text-align:right;">
0.2221435
</td>
</tr>
<tr>
<td style="text-align:right;">
19
</td>
<td style="text-align:right;">
0.8350879
</td>
<td style="text-align:right;">
0.2928427
</td>
</tr>
<tr>
<td style="text-align:right;">
20
</td>
<td style="text-align:right;">
0.6163942
</td>
<td style="text-align:right;">
0.1492838
</td>
</tr>
<tr>
<td style="text-align:right;">
21
</td>
<td style="text-align:right;">
0.8327854
</td>
<td style="text-align:right;">
0.0571125
</td>
</tr>
<tr>
<td style="text-align:right;">
22
</td>
<td style="text-align:right;">
0.7558969
</td>
<td style="text-align:right;">
0.2731436
</td>
</tr>
<tr>
<td style="text-align:right;">
23
</td>
<td style="text-align:right;">
0.6581821
</td>
<td style="text-align:right;">
0.1814247
</td>
</tr>
<tr>
<td style="text-align:right;">
24
</td>
<td style="text-align:right;">
0.7604780
</td>
<td style="text-align:right;">
0.1831064
</td>
</tr>
<tr>
<td style="text-align:right;">
25
</td>
<td style="text-align:right;">
0.7299039
</td>
<td style="text-align:right;">
0.1463419
</td>
</tr>
<tr>
<td style="text-align:right;">
26
</td>
<td style="text-align:right;">
0.9415226
</td>
<td style="text-align:right;">
0.2894229
</td>
</tr>
<tr>
<td style="text-align:right;">
27
</td>
<td style="text-align:right;">
0.6286622
</td>
<td style="text-align:right;">
0.1635177
</td>
</tr>
<tr>
<td style="text-align:right;">
28
</td>
<td style="text-align:right;">
0.6672417
</td>
<td style="text-align:right;">
0.0677156
</td>
</tr>
<tr>
<td style="text-align:right;">
29
</td>
<td style="text-align:right;">
0.6071370
</td>
<td style="text-align:right;">
0.2382317
</td>
</tr>
<tr>
<td style="text-align:right;">
30
</td>
<td style="text-align:right;">
0.7590172
</td>
<td style="text-align:right;">
0.1941605
</td>
</tr>
</tbody>
</table>

<br>

<table class=" lightable-classic" style="font-family: &quot;Arial Narrow&quot;, &quot;Source Sans Pro&quot;, sans-serif; margin-left: auto; margin-right: auto;">
<caption>

NIDA Skill Parameters

5 skills x 2 parameters
</caption>
<thead>
<tr>
<th style="text-align:left;">
Skill
</th>
<th style="text-align:right;">
Hit (1 - Slip)
</th>
<th style="text-align:right;">
Guess
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
Skill 1
</td>
<td style="text-align:right;">
0.95
</td>
<td style="text-align:right;">
0.25
</td>
</tr>
<tr>
<td style="text-align:left;">
Skill 2
</td>
<td style="text-align:right;">
0.70
</td>
<td style="text-align:right;">
0.10
</td>
</tr>
<tr>
<td style="text-align:left;">
Skill 3
</td>
<td style="text-align:right;">
0.85
</td>
<td style="text-align:right;">
0.25
</td>
</tr>
<tr>
<td style="text-align:left;">
Skill 4
</td>
<td style="text-align:right;">
0.80
</td>
<td style="text-align:right;">
0.10
</td>
</tr>
<tr>
<td style="text-align:left;">
Skill 5
</td>
<td style="text-align:right;">
0.60
</td>
<td style="text-align:right;">
0.10
</td>
</tr>
</tbody>
</table>

<br>

Based on the true values (learner skill mastery ($\alpha$), Q matrix,
Hit ($h$), and Guess ($g$) parameters, 20 sets of response data matrices
were created using the DINA model described below. Each response data
matrix was for 200 learners and 30 items. <br>

The function of a correct item response under DINA is described as
follows:  
$$P_{ij} = h_{j}^{\eta_{ij}}g_{j}^{(1 - \eta_{ij})}$$
$$\eta_{ij} = \prod_{k = 1}^{K} \alpha_{ik}^{q_{jk}}$$

$\alpha_{ik}$: learner skill mastery per skill $k$ by each learner $i$  
$h_{j}$: 1 - slip per item $j$  
$g_{j}$: guess per item $j$  
<br>

Another 20 sets of response data matrices were created using the NIDA
model for 200 learners and 30 items. The function of a correct item
response under NIDA is described as follows:  
$$P_{ij} = \prod_{k = 1}^{K} (h_{k}^{\alpha_{ik}}g_{k}^{(1 - \alpha_{ik})})^{q_{jk}}$$

$\alpha_{ik}$: learner skill mastery per skill $k$ by each learner $i$  
$h_{k}$: 1 - slip per skill $k$  
$g_{k}$: guess per skill $k$  
<br>

# 2. Rasch Model Parameter Estimation

<br> We applied the Rasch model to each response data matrix and
calculated item difficulty and skill estimates. The average item
difficulty and skill estimates from 20 data sets were calculated for the
DINA and NIDA models, respectively. <br>

The function of a correct item response under Rasch is described as
follows:  
$$P_{ij} = \frac{exp(\theta_{i} - \beta_{j})}{1 + exp(\theta_{i} - \beta_{j})}$$

$\theta_{i}$: learner skill $i$  
$\beta_{j}$: item difficulty $j$

<br>

# 3. Parameter Comparison

<br> As we calculated skill estimates by fitting the Rasch model to the
DINA and NIDA simulated data, we compared these skill estimates with the
true values that were used for simulating the DINA and NIDA response
data. **The comparison showed that the Rasch skill estimates from both
DINA and NIDA simulated data were perfectly correlated with the true
$\alpha$ (skill mastery) values.** <br>

![](github.rmarkdown.testing_files/figure-gfm/unnamed-chunk-6-1.png)<!-- -->
<br>

## 3.1. DINA vs. Rasch

<br> We compared the Rasch item difficulty estimates with the true item
hit $h$ and guess $g$ values that were used for simulating the DINA
response data. **We found that the Rasch item difficulty estimates from
the DINA simulated data were negatively correlated with the item hit $h$
parameters ($\rho$ = -0.41), but the relationship with the item guess
$g$ parameters was weak ($\rho$ = -0.1).** <br>

![](github.rmarkdown.testing_files/figure-gfm/unnamed-chunk-7-1.png)<!-- -->

<br>

## 3.2. NIDA vs. Rasch

<br> We compared the Rasch skill estimates with the true skill $\alpha$
values that were used for simulating the NIDA response data. **The NIDA
skill mastery patterns that included Skill 5 (with the lowest hit $h$
(the highest slip) parameter) and Skill 2 (with the second lowest hit
$h$ parameter) were related to lower Rasch skill estimates. The NIDA
skill mastery patterns that included Skill 1 (with the highest hit $h$
parameter) were related to higher Rasch skill estimates.** <br>

<table class=" lightable-classic" style="font-family: &quot;Arial Narrow&quot;, &quot;Source Sans Pro&quot;, sans-serif; margin-left: auto; margin-right: auto;">
<caption>
NIDA Skill Parameters vs. IRT Skill Estimates
</caption>
<thead>
<tr>
<th style="text-align:left;">
NIDA Skill Mastery Pattern
</th>
<th style="text-align:right;">
IRT Skill Estimates
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
0.0.0.0.1
</td>
<td style="text-align:right;">
-1.2693237
</td>
</tr>
<tr>
<td style="text-align:left;">
0.0.1.0.0
</td>
<td style="text-align:right;">
-1.1413860
</td>
</tr>
<tr>
<td style="text-align:left;">
1.0.0.0.0
</td>
<td style="text-align:right;">
-1.1343732
</td>
</tr>
<tr>
<td style="text-align:left;">
0.0.1.0.1
</td>
<td style="text-align:right;">
-0.7963927
</td>
</tr>
<tr>
<td style="text-align:left;">
0.1.0.1.0
</td>
<td style="text-align:right;">
-0.6212416
</td>
</tr>
<tr>
<td style="text-align:left;">
0.1.1.0.0
</td>
<td style="text-align:right;">
-0.6148298
</td>
</tr>
<tr>
<td style="text-align:left;">
0.0.1.1.0
</td>
<td style="text-align:right;">
-0.5826221
</td>
</tr>
<tr>
<td style="text-align:left;">
1.1.0.0.0
</td>
<td style="text-align:right;">
-0.5768498
</td>
</tr>
<tr>
<td style="text-align:left;">
1.0.1.0.0
</td>
<td style="text-align:right;">
-0.5566502
</td>
</tr>
<tr>
<td style="text-align:left;">
1.0.0.1.0
</td>
<td style="text-align:right;">
-0.4535163
</td>
</tr>
<tr>
<td style="text-align:left;">
0.1.1.0.1
</td>
<td style="text-align:right;">
-0.2223022
</td>
</tr>
<tr>
<td style="text-align:left;">
0.1.0.1.1
</td>
<td style="text-align:right;">
-0.1746597
</td>
</tr>
<tr>
<td style="text-align:left;">
1.0.1.0.1
</td>
<td style="text-align:right;">
-0.1604756
</td>
</tr>
<tr>
<td style="text-align:left;">
1.1.1.0.0
</td>
<td style="text-align:right;">
-0.0361790
</td>
</tr>
<tr>
<td style="text-align:left;">
0.0.1.1.1
</td>
<td style="text-align:right;">
-0.0333555
</td>
</tr>
<tr>
<td style="text-align:left;">
0.1.1.1.0
</td>
<td style="text-align:right;">
-0.0162578
</td>
</tr>
<tr>
<td style="text-align:left;">
1.1.0.1.0
</td>
<td style="text-align:right;">
0.0359713
</td>
</tr>
<tr>
<td style="text-align:left;">
1.0.0.1.1
</td>
<td style="text-align:right;">
0.0515063
</td>
</tr>
<tr>
<td style="text-align:left;">
1.0.1.1.0
</td>
<td style="text-align:right;">
0.0623549
</td>
</tr>
<tr>
<td style="text-align:left;">
1.1.1.0.1
</td>
<td style="text-align:right;">
0.3867322
</td>
</tr>
<tr>
<td style="text-align:left;">
0.1.1.1.1
</td>
<td style="text-align:right;">
0.4258707
</td>
</tr>
<tr>
<td style="text-align:left;">
1.0.1.1.1
</td>
<td style="text-align:right;">
0.5248952
</td>
</tr>
<tr>
<td style="text-align:left;">
1.1.1.1.0
</td>
<td style="text-align:right;">
0.6063866
</td>
</tr>
<tr>
<td style="text-align:left;">
1.1.0.1.1
</td>
<td style="text-align:right;">
0.6150383
</td>
</tr>
<tr>
<td style="text-align:left;">
1.1.1.1.1
</td>
<td style="text-align:right;">
1.0730383
</td>
</tr>
</tbody>
</table>

<br>

# 4. Discussion

<br>

We could confirm that the IRT based skill estimates are aligned with the
CDM based skill estimates when we analyze the same data using these two
different models. We could also find relationships between the IRT
parameters and the CDM hit $h$ parameters (see Sections 3.1 and 3.2).
However, it was not clear or easy to find any relationships between the
Rasch parameters and the guess $g$ parameters from both the DINA (item
level) and NIDA (skill level) models. To explore further, we can fit
either 2PL or 3PL IRT models to the simulated response data and compare
the item discrimination parameters with the CDM guess parameters.
