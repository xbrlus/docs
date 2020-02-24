<html lang="en-US">
<head>
<link rel="shortcut icon" href="https://xbrl.us/wp-content/themes/xbrl-jurisdiction/images/favicon.ico" />
  <!--
  <link href="//maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css" rel="stylesheet">
  -->
  <link href="//xbrl.us/wp-content/js/font-awesome-4.1.min.css" rel="stylesheet">

  <link href='//fonts.googleapis.com/css?family=Lato:400,700' rel='stylesheet' type='text/css'>
  <link href='//fonts.googleapis.com/css?family=Roboto:300,300italic,400,500,500italic,700' rel='stylesheet' type='text/css'>
  <link href='//fonts.googleapis.com/css?family=Oswald:400,700' rel='stylesheet' type='text/css'>
  <link href='//fonts.googleapis.com/css?family=Molengo:400,700' rel='stylesheet' type='text/css'>
  <link href='//fonts.googleapis.com/css?family=Arimo:400,700' rel='stylesheet' type='text/css'>

<!--
<link href="//maxcdn.bootstrapcdn.com/font-awesome/4.2.0/css/font-awesome.min.css" rel="stylesheet">
-->
<link href="//xbrl.us/wp-content/js/font-awesome-4.2.min.css" rel="stylesheet">
  <link rel="stylesheet" href="https://xbrl.us/wp-content/themes/xbrl-jurisdiction/bootstrap/css/bootstrap.min.css" type="text/css" />
<link rel="stylesheet" type="text/css" media="all" href="https://xbrl.us/wp-content/themes/xbrl-jurisdiction/style.css" />
</head>
<body style="text-align: left !important;">
<h1>Taxonomy Development Handbook</h1>
<p>The Taxonomy Development Handbook (TDH) is a comprehensive guide that directs regulators, industry experts, and businesses through a practical, consistent roadmap to building high quality data standards using XBRL.</p>  

<!-- <p>This draft release was developed by the XBRL US Domain Steering Committee (DSC) for a 9<strong>0-day public review period that ends on February 21, 2020</strong>. The DSC requests comments about the following:</p>  

<ul>
<li>Areas/topics that were not included but should be added to the document</li>
<li>Suggested revisions or corrections to the content</li>
<li>Suggested clarifications</li>
</ul>
<p><strong>When commenting, please indicate the numbered section of the document to which your comment pertains.</strong></p>  -->

<h5 class="tdh_091">Domain Steering Committee</h5>
<h2 class="tdh_094">A Guide for XBRL Taxonomy Developers</h2>
<h3 class="tdh_093">Public Comment Draft #1 (November 2019)</h3>
<h4 class="tdh_025"><a name="toc"></a>Table of Contents</h4>
<table class="tdh_238" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_196">
<td class="tdh_193"><a href="#a_Toc24107524">1  Introduction</a></td>
<td class="tdh_200"><a href="#a_Toc24107524">1</a></td>
<td class="tdh_192"><a href="#a_Toc24107559"> 6.3  Using Arelle</a></td>
<td class="tdh_200"><a href="#a_Toc24107559">86</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107525"> 1.1  Overview</a></td>
<td class="tdh_200"><a href="#a_Toc24107525">1</a></td>
<td class="tdh_192"><a href="#a_Toc24107560"> 6.4  The Importance of Public Exposure</a></td>
<td class="tdh_200"><a href="#a_Toc24107560">88</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107526"> 1.2  XBRL US and Its Mission</a></td>
<td class="tdh_200"><a href="#a_Toc24107526">2</a></td>
<td class="tdh_192"><a href="#a_Toc24107561"> 6.5  Guidance</a></td>
<td class="tdh_200"><a href="#a_Toc24107561">88</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107527"> 1.3  XBRL: the eXtensible Business Reporting Language</a></td>
<td class="tdh_200"><a href="#a_Toc24107527">3</a></td>
<td class="tdh_193"><a href="#a_Toc24107562">7  Documenting a Taxonomy</a></td>
<td class="tdh_200"><a href="#a_Toc24107562">89</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107528"> 1.4  What Is in this Document</a></td>
<td class="tdh_200"><a href="#a_Toc24107528">7</a></td>
<td class="tdh_192"><a href="#a_Toc24107563"> 7.1  How to Use This Chapter</a></td>
<td class="tdh_200"><a href="#a_Toc24107563">90</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_193"><a href="#a_Toc24107529">2  An Introduction to XBRL</a></td>
<td class="tdh_200"><a href="#a_Toc24107529">10</a></td>
<td class="tdh_192"><a href="#a_Toc24107564"> 7.2  The <i>Taxonomy White Paper</i></a></td>
<td class="tdh_200"><a href="#a_Toc24107564">91</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107530"> 2.1  eXtensible Business Reporting Language</a></td>
<td class="tdh_200"><a href="#a_Toc24107530">10</a></td>
<td class="tdh_192"><a href="#a_Toc24107565"> 7.3  The <i>Taxonomy Guide</i></a></td>
<td class="tdh_200"><a href="#a_Toc24107565">91</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107531"> 2.2  How Does XBRL Represent Data?</a></td>
<td class="tdh_200"><a href="#a_Toc24107531">14</a></td>
<td class="tdh_192"><a href="#a_Toc24107566"> 7.4  The <i>Preparer Guide</i></a></td>
<td class="tdh_200"><a href="#a_Toc24107566">95</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107532"> 2.3  Machine-readability</a></td>
<td class="tdh_200"><a href="#a_Toc24107532">26</a></td>
<td class="tdh_192"><a href="#a_Toc24107567"> 7.5  The <i>Data Consumer Guide</i></a></td>
<td class="tdh_200"><a href="#a_Toc24107567">100</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107533"> 2.4  The Taxonomy</a></td>
<td class="tdh_200"><a href="#a_Toc24107533">27</a></td>
<td class="tdh_192"><a href="#a_Toc24107568"> 7.6  Updates and Release Notes</a></td>
<td class="tdh_200"><a href="#a_Toc24107568">104</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_193"><a href="#a_Toc24107534">3  Structuring Data</a></td>
<td class="tdh_200"><a href="#a_Toc24107534">34</a></td>
<td class="tdh_193"><a href="#a_Toc24107569">8  Taxonomy Governance</a></td>
<td class="tdh_200"><a href="#a_Toc24107569">105</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107535"> 3.1  Introduction</a></td>
<td class="tdh_200"><a href="#a_Toc24107535">34</a></td>
<td class="tdh_192"><a href="#a_Toc24107570"> 8.1  The Taxonomy Lifecycle</a></td>
<td class="tdh_200"><a href="#a_Toc24107570">105</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107536"> 3.2  Typical Data</a></td>
<td class="tdh_200"><a href="#a_Toc24107536">34</a></td>
<td class="tdh_192"><a href="#a_Toc24107571"> 8.2  Effective Communication</a></td>
<td class="tdh_200"><a href="#a_Toc24107571">110</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107537"> 3.3  Creating an XBRL Data Model</a></td>
<td class="tdh_200"><a href="#a_Toc24107537">37</a></td>
<td class="tdh_193"><a href="#a_Toc24107572">9  Success Stories</a></td>
<td class="tdh_200"><a href="#a_Toc24107572">111</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107538"> 3.4  Components of an XBRL Data Model</a></td>
<td class="tdh_200"><a href="#a_Toc24107538">43</a></td>
<td class="tdh_192"><a href="#a_Toc24107573"> 9.1  Banking in the United States</a></td>
<td class="tdh_200"><a href="#a_Toc24107573">111</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107539"> 3.5  Implementing the XBRL Data Model</a></td>
<td class="tdh_200"><a href="#a_Toc24107539">48</a></td>
<td class="tdh_192"><a href="#a_Toc24107574"> 9.2  Business to Government Reporting</a></td>
<td class="tdh_200"><a href="#a_Toc24107574">113</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107540"> 3.6  Extensibility</a></td>
<td class="tdh_200"><a href="#a_Toc24107540">53</a></td>
<td class="tdh_192"><a href="#a_Toc24107575"> 9.3  Work-in-Process Reporting for Surety Underwriting</a></td>
<td class="tdh_200"><a href="#a_Toc24107575">114</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107541"> 3.7  Moving Forward</a></td>
<td class="tdh_200"><a href="#a_Toc24107541">55</a></td>
<td class="tdh_192"><a href="#a_Toc24107576"> 9.4  Public Company Reporting in the United States</a></td>
<td class="tdh_200"><a href="#a_Toc24107576">116</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_193"><a href="#a_Toc24107542">4  Assessing Overall Project Scope</a></td>
<td class="tdh_200"><a href="#a_Toc24107542">56</a></td>
<td class="tdh_192"></td>
<td class="tdh_200"></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107543"> 4.1  Define the Project&#8217;s Goals</a></td>
<td class="tdh_200"><a href="#a_Toc24107543">56</a></td>
<td class="tdh_192"></td>
<td class="tdh_200"></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107544"> 4.2  Identifying and Engaging Stakeholders</a></td>
<td class="tdh_200"><a href="#a_Toc24107544">58</a></td>
<td class="tdh_193">Appendices</td>
<td class="tdh_200"></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107545"> 4.3  Define the Scope of the Taxonomy</a></td>
<td class="tdh_200"><a href="#a_Toc24107545">59</a></td>
<td class="tdh_192"><a href="#a_Toc24107577">Appendix A  XBRL and XML Supporting Information</a></td>
<td class="tdh_200"><a href="#a_Toc24107577">120</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107546"> 4.4  Identifying Relevant Systems</a></td>
<td class="tdh_200"><a href="#a_Toc24107546">60</a></td>
<td class="tdh_192"><a href="#a_Toc24107578">Appendix B  Taxonomy Creation Checklist</a></td>
<td class="tdh_200"><a href="#a_Toc24107578">121</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107547"> 4.5  Identifying Regulatory or NGO Requirements</a></td>
<td class="tdh_200"><a href="#a_Toc24107547">60</a></td>
<td class="tdh_192"><a href="#a_Toc24107579">Appendix C  <i>Taxonomy White Paper</i> Outline and Template</a></td>
<td class="tdh_200"><a href="#a_Toc24107579">123</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107548"> 4.6  Other Requirements and Considerations</a></td>
<td class="tdh_200"><a href="#a_Toc24107548">60</a></td>
<td class="tdh_192"><a href="#a_Toc24107580">Appendix D  <i>XBRL Overview</i> Outline and Template</a></td>
<td class="tdh_200"><a href="#a_Toc24107580">125</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107549"> 4.7  Measuring Success</a></td>
<td class="tdh_200"><a href="#a_Toc24107549">64</a></td>
<td class="tdh_192"><a href="#a_Toc24107581">Appendix E  <i>Taxonomy Guide</i> Outline and Template</a></td>
<td class="tdh_200"><a href="#a_Toc24107581">131</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_193"><a href="#a_Toc24107550">5  Building a Transport Data Model</a></td>
<td class="tdh_200"><a href="#a_Toc24107550">65</a></td>
<td class="tdh_192"><a href="#a_Toc24107582">Appendix F  <i>Preparer Guide</i> Outline and Template</a></td>
<td class="tdh_200"><a href="#a_Toc24107582">136</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107551"> 5.1  Getting Started</a></td>
<td class="tdh_200"><a href="#a_Toc24107551">65</a></td>
<td class="tdh_192"><a href="#a_Toc24107583">Appendix G  <i>Data Consumer Guide</i> Outline and Template</a></td>
<td class="tdh_200"><a href="#a_Toc24107583">141</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107552"> 5.2  Developing a Model</a></td>
<td class="tdh_200"><a href="#a_Toc24107552">65</a></td>
<td class="tdh_192"><a href="#a_Toc24107584">Appendix H  XBRL US — Taxonomy Approval Metrics</a></td>
<td class="tdh_200"><a href="#a_Toc24107584">145</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107553"> 5.3  Transforming a Data Model to a Transport Model</a></td>
<td class="tdh_200"><a href="#a_Toc24107553">69</a></td>
<td class="tdh_192"><a href="#a_Toc24107585">Appendix I  Intellectual Property Status</a></td>
<td class="tdh_200"><a href="#a_Toc24107585">149</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107554"> 5.4  Development Choices</a></td>
<td class="tdh_200"><a href="#a_Toc24107554">74</a></td>
<td class="tdh_192"><a href="#a_Toc24107586"> I.1.  Terms and Conditions: XBRL US Public Review</a></td>
<td class="tdh_200"><a href="#a_Toc24107586">149</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107555"> 5.5  Validation</a></td>
<td class="tdh_200"><a href="#a_Toc24107555">77</a></td>
<td class="tdh_192"><a href="#a_Toc24107587">Appendix J  Document Revision Status</a></td>
<td class="tdh_200"><a href="#a_Toc24107587">151</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_193"><a href="#a_Toc24107556">6  The Mechanics of Taxonomy Development</a></td>
<td class="tdh_200"><a href="#a_Toc24107556">79</a></td>
<td class="tdh_192"><a href="#a_Toc24107588">Appendix K  Revisions and Public Comments</a></td>
<td class="tdh_200"><a href="#a_Toc24107588">152</a></td>
</tr>
<tr class="tdh_196">
<td class="tdh_192"><a href="#a_Toc24107557"> 6.1  Workflow</a></td>
<td class="tdh_200"><a href="#a_Toc24107557">79</a></td>
<td class="tdh_192"><a href="#a_Toc24107589">Glossary</a></td>
<td class="tdh_200"><a href="#a_Toc24107589">153</a></td>
</tr>
<tr class="tdh_196" style="border-bottom-color: none !important;">
<td class="tdh_192" style="border-bottom: 0px !important;"><a href="#a_Toc24107558"> 6.2  Preparing and Generating the Taxonomy</a></td>
<td class="tdh_200" style="border-bottom: 0px !important;"><a href="#a_Toc24107558">79</a></td>
<td class="tdh_192" style="border-bottom: 0px !important;"><a href="#a_Toc24107590">Index</a></td>
<td class="tdh_200" style="border-bottom: 0px !important;"><a href="#a_Toc24107590">165</a></td>
</tr>
</tbody>
</table>
<p class="tdh_025">Preface</p>  

<div class="tdh_066">In 2016, I was asked by XBRL US: &#8220;can we make a guide to help people and organizations build taxonomies?&#8221; This handbook is that guide, and it is the result of the effort of many people and organizations as part of the XBRL US Domain Steering Committee over the past few years.</div>
<div class="tdh_066">Up until now, the available information from XBRL International and XBRL US about XBRL was highly technical. While satisfying the need for specifications, these documents do not give an easy, &#8220;all-in-one&#8221; source of information about development using the XBRL platform. To put it simply: there was a wealth of information about <i>what</i> XBRL is, but there was a sharp lack of an explanation about <i>how</i> to use it effectively to transport and organize data. Therefore, the primary objective of the <i>Taxonomy Development Handbook</i> is to bridge this gap between technical description and practical application. It does this while providing an easy to understand introduction to XBRL and its capabilities, with a great deal of focus on how to build and maintain a taxonomy. Ideally, using this handbook the uninitiated can get a gasp of the XBRL model and terminology with only a few hours of study. In addition, we cover the high points of how to get an XBRL development project started, basic taxonomy documentation requirements, how to oversee the implementation of standards, and ways to manage the ongoing maintenance of a taxonomy.</div>
<div class="tdh_066">XBRL is uniquely suited to represent structured data for reporting purposes, and the information it expresses is comparable across different reports and historically stable. There is no other format or specification that provides support for unique data point identification, time domain structure, and the expression of multi-dimensionality all while describing a semantic data model. In addition, a data consumption system can examine an XBRL fact and have a well-defined understanding of its meaning and disclosure purpose without looking beyond the taxonomy itself, which is efficient in both time and cost.</div>
<div class="tdh_066">I believe XBRL is uniquely positioned to address the needs of many data providers, regulators, analysts, aggregators, and consumers. It is used all over the world in various forms to answer regulatory and private sector data exchange requirements. As Campbell Pryde, the President and CEO of XBRL, stated, &#8220;up until now, XBRL is the best kept secret&#8221; when addressing the volume of need and opportunities for structured data and yet the fact that many organizations are unaware of XBRL&#8217;s capabilities. We think it is high time that secret be made open and obvious for data communities. With this document, we think XBRL is ready to be discovered as a robust, powerful, and flexible data transport tool.</div>
<div class="tdh_066">As set out in the mission for the Domain Steering Committee, our goal is to support the technology and development efforts of XBRL US necessary to meet the business reporting needs of key markets in the United States. This includes approving taxonomy development work, performing quality control, providing feedback to working groups, and guiding taxonomy developers in designing their own XBRL solutions. Hopefully this document is your first step to a successful project. XBRL US and the Domain Steering Committee stand ready to assist you in your efforts.</div>
<p class="tdh_069">Scott A. Theis</p>  

<p class="tdh_069">Chairman, Domain Steering Committee, XBRL US<br />
President/CEO, Novaworks, LLC</p>  

<div class="content-full">
<div class="tdh_028"><a name="tc_01_a"></a><a name="a_Toc24107524"></a><a name="a_Toc23337670"></a><a name="a_Ref19622713"></a>1   Introduction</div>
<div class="tdh_027"><a name="tc_02_a"></a><a name="a_Toc24107525"></a><a name="a_Toc23337671"></a>1.1   Overview</div>
<p class="tdh_020"><span class="tdh_024">1.1.1     </span>Scope and Goal</p>  

<div class="tdh_066">The purpose of this document is to provide a basic reference and useful guidelines for XBRL taxonomy development, implementation, and maintenance. Sections of this document discuss XBRL, why it was created, its advantages as a data transport tool, and how it compares to other systems. Other parts focus on proper taxonomy creation, and others cover the importance of how that taxonomy is designed, controlled, and implemented to maintain usability and data integrity. Since XBRL is more than a simple data transport mechanism, a well-defined data structure is critical to successful deployment. As such, this guide will also review certain aspects of system development, including data modeling, the mechanics of taxonomy development, and defining guidelines for the end result. Finally, any XBRL taxonomy is only as powerful as how well it is governed. Methods for maintaining a taxonomy once it has been designed and implemented to ensure proper validation, transmission, reception, and interpretation are discussed.</div>
<div class="tdh_066">In total, this document will hopefully provide useful instruction and guidance so that taxonomy developers can be successful in creating and implementing their own XBRL taxonomy, no matter the circumstances, constraints, and requirements of their project. Although this document proceeds in a linear, &#8220;story-telling&#8221; fashion, readers should feel free to skip parts or any section not relevant to their needs or whose content is already familiar to them.</div>
<p class="tdh_020"><span class="tdh_024">1.1.2     </span>Audience</p>  

<div class="tdh_066">This document has been written to provide the reader with basic information to get started in the development of a taxonomy. Since such development does not happen in a vacuum, years of experience in developing and managing taxonomies have been distilled in a useful guide for the creation, deployment, and on-going management of an XBRL taxonomy.</div>
<div class="tdh_066">The reader is assumed to have some familiarity with business data models, and it is assumed that the reader is either researching, or has been tasked with, building a system to transport and redistribute business or business-like data. A familiarity with XBRL is not required; XBRL constructs will be explained in detail so inexperienced readers can be introduced to necessary ideas as they follow along in the process of taxonomy development. XML experience also is not required as this guide will again instruct readers in the pertinent details and direct them to outside resources for more information.</div>
<div class="tdh_066">At the end of the journey, readers should have a system in place that answers all the specified requirements, is easy to understand, easy to implement, and extensible as required and desired.</div>
<p class="tdh_020"><span class="tdh_024">1.1.3     </span>Terminology</p>  

<div class="tdh_066">Because XBRL is an evolving, open-source entity, there are multiple ways of documenting and describing it. Readers who are familiar with XBRL/XML may be surprised at some of the new and different terminology being used within this guide. These vocabulary choices are the result of a combination of things. First, to be in alignment with the proposed XBRL Open Information Model, certain terms such as &#8220;context&#8221; have been replaced with more flexible terms such as &#8220;dimension.&#8221; The terms used in this document should be in better alignment with current business and information systems modeling vocabulary while staying true to the underlying meaning and capabilities of XBRL. Second, through knowledge and experience, the authors of this document have tried to clean up and make consistent some of the terminology used in the past and avoid the blanket use of various ambiguous words such as &#8220;properties,&#8221; &#8220;meta data,&#8221; or &#8220;attributes.&#8221; Third, while XBRL has commonly been implemented to express accounting information, accounting is only a subset of the overall reporting capabilities of XBRL. Therefore, examples and terminology have been employed in this document to represent a general, wider range of reporting environments and circumstances.</div>
<div class="tdh_066">Readers should also note in the following chapters the term <i>dimension</i> can refer to both the dimensionality of the data model and the XBRL construct dimension. Sometimes these truly are interchangeable, as data model dimensionality is represented in XBRL with XBRL dimensions and</div>
<p><!-- Field: Page; Sequence: 6; Options: NewSection; Value: 1 --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->1<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">dimensional constructs. However, if the text specifically refers to the dimensionality of the data model, it will be termed a <i>data dimension.</i> If the text is describing an XBRL construct, it will be termed an <i>XBRL dimension.</i></div>
<div class="tdh_066">In a similar vein, to distinguish between originating data models and the XBRL representations of them, data model line items or columns are capitalized in the text and match the examples typically provided in tables or figures. XBRL concept names follow the guidelines of the <a href="https://xbrl.us/wp-content/uploads/2017/09/style-guide-20170907.pdf"><span class="tdh_035"><i><u>XBRL US Style Guide</u></i></span></a> and are presented in upper camel case. Values (such as fact values or property values) are shown in quotation marks (such as &#8220;12.5&#8221; or &#8220;true&#8221;).</div>
<p class="tdh_020"><span class="tdh_024">1.1.4     </span>The End Result</p>  

<div class="tdh_066">No matter the industry, specific requirements, or reporting needs, the ultimate goal at the end of the taxonomy development process is to create data that is meaningful to consumers. This is true regardless of what that data is and whether it is consumed in real time or collected in offline analyses. The accuracy, usability, and predictability for the consumer is vitally important, and the end result of development should be robust enough to deliver consistent results on all of these fronts. Balanced with this, though, the burden placed on the preparers must be reasonable. There should not be significant requirements for preparers that seem too complicated or byzantine, and the amount of time and cost associated with preparing and validating reports cannot be prohibitive. The solution, whatever it is, must be maintainable and open to future changes, which also means it must be self-describing, so those changes do not cause disruption for data consumers and preparers alike.</div>
<div class="tdh_066">XBRL accomplishes these aims and can produce the necessary result: usable, meaningful data. XBRL also serves as a method of transporting data in a way that is self-describing and self-contained. An XBRL taxonomy can serve as the center of any information supply chain, connecting preparers to consumers in a structured, logical way.</div>
<div class="tdh_027"><a name="a_Toc24107526"></a><a name="a_Toc23337672"></a>1.2   XBRL US and Its Mission</div>
<div class="tdh_066"><span class="tdh_023">XBRL US is the non-profit </span>consortium <span class="tdh_023">for XBRL business reporting standards in the United States. It is the US jurisdiction of XBRL International (XII). While XII is responsible for maintaining the technical XBRL specification, XBRL US focuses on education, awareness building, advocacy, and development work in the United States&#8217; marketplace. XBRL US is a membership organization, and its membership represents many links within the business information supply chain, including accounting firms, businesses, data providers, data consumers, software providers, database and analytical tool providers, as well as other nonprofit organizations. The mission of XBRL US is to support the implementation of business reporting standards through the development of taxonomies for use by the public and private sectors within the US, with a goal of interoperability between sectors, and by promoting XBRL adoption through marketplace collaboration. </span></div>
<div class="tdh_066">XBRL US has developed taxonomies for financial accounting, as well as credit rating and mutual fund reporting under contract with the United States Securities and Exchange Commission. It has also developed industry-specific taxonomies for corporate actions, solar financing, surety processing, and municipal financial reporting.</div>
<div class="tdh_066">XBRL US&#8217; website also features access to a repository database for XBRL information and an application programming interface (API) for software development. The underlying code for the repository and API is also available so members can setup private databases. This is an important part of the overall mission of XBRL US: to provide for consistent structure, useful tools, and guidelines for data integrity for the current and eventual consumers of XBRL.</div>
<div class="tdh_066">This document is just one of XBRL US&#8217; many educational and outreach ef<span class="tdh_023">forts to promote stable and standardized reporting of business information. For more information and other resources, visit XBRL US&#8217; website at https://xbrl.us/.</span></div>
<p><!-- Field: Page; Sequence: 7 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->2<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_027"><a name="a_Toc24107527"></a><a name="a_Toc23337673"></a>1.3   XBRL: the eXtensible Business Reporting Language</div>
<p class="tdh_020"><span class="tdh_024">1.3.1     </span>XBRL Provides a Platform to Give Data Meaning</p>  

<div class="tdh_066">This is the age of big data, and people have an expectation that any piece of information should be readily available at their fingertips. Furthermore, not only should that information be accessible, but the exact form in which it is presented must be suited to an individual&#8217;s or an organization&#8217;s specific needs. Whether information is gathered using an everyday search engine or specialized software (that may analyze everything from vehicle movements to smart phone habits), having the right data in the right format is key. A lack of depth, context, and consistency significantly reduces the data&#8217;s usefulness, utility, and the ability of consumers to interpret the information. Despite advances in data science, conveying the deeper meaning of information is a continuing struggle. The consistency and integrity of the data itself is important, but how can that data be interpreted meaningfully without context? For example, some data points can be very simple: &#8220;on/off&#8221; (or 1 and 0). However, this binary representation of information says very little. What is on or off? In order to know more, a concept must be added: the &#8220;light&#8221; is &#8220;on.&#8221; Even more information can be appended through additional concepts. A location can be specified: the &#8220;porch&#8221; &#8220;light&#8221; is &#8220;on.&#8221; A time may be indicated as well, which leads to a more interpretable statement of data: the &#8220;porch&#8221; &#8220;light&#8221; is &#8220;on&#8221; at &#8220;18:05 UTC.&#8221;</div>
<div class="tdh_066">Without the ability to provide this type of meaningful information about a data point, most people would agree that the value of the data diminishes. Data standards that focus on the interchange of data points are designed to provide additional context about data so that systems and analysts can manage and utilize that data appropriately. Further, these type of data standards must also provide a semantic framework for that meaning to be interpreted appropriately by an external computer system or person.</div>
<div class="tdh_066">Before examining standards like these, the process of assigning meaning to data should be examined a little more closely. What meaning needs to be included with a data point to make certain it is clearly understood between systems and people will be the first part of determining how that data and its relevant contextual information needs to be structured.</div>
<p class="tdh_099"><img class="tdh_163" src="http://files.xbrl.us/images/tdh/tdh_p1_002.jpg" alt="A close up of a logo Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref16068055"></a>Figure 1-1. Possible types of information that could accompany a simple numeric data point</p>  

<p><!-- Field: Page; Sequence: 8 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->3<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">On the left side of Figure 1-1, there is a piece of primitive numeric data: &#8220;1234.&#8221; On its own, that data point only relays information to a reader if that recipient is already familiar with its context and purpose. For the purposes of this discussion, that data point can be referred to as a <i>fact</i>. In layers, meaning can be added to the fact by defining precision, scaling, units, and other similar information. Contextual meaning can also be supplied through another layer containing information such as time and location.</div>
<div class="tdh_066">Finally, the fact can be identified with a <i>concept</i>. Depending on the semantic component of the standard being used to represent the data, this conceptual information could be quite detailed and include a wealth of additional meaning. As mentioned previously, structured data standards offer defined systems to represent data in this way, by adding layers of meaningful context that provide useful, pre-determined ways to interpret that data. XBRL is one such standard.</div>
<p class="tdh_020"><span class="tdh_024">1.3.2     </span>Background</p>  

<div class="tdh_066">At the turn of the century, an effort was undertaken to effectively represent business information for relaying and reporting data to government agencies. XBRL was born to address the idea of globally exchanging business information in a standard format. Beginning in 1998, numerous accountants and other business specialists, including the American Institute of Certified Public Accountants (AICPA), worked together to develop the early XBRL specifications and form what would eventually become XBRL International. The first XBRL specification was published in July 2000. The <a href="https://specifications.xbrl.org/work-product-index-group-base-spec-base-spec.html"><span class="tdh_035"><i><u>XBRL Specification</u></i></span></a>, which has been stable since its release, was introduced in December 2003. Since then, XBRL has become widely used as a standard of transmitting structured business information.</div>
<p class="tdh_020"><span class="tdh_024">1.3.3     </span>Conveying Information</p>  

<div class="tdh_066">Companies report data to regulators and other entities using a multitude of syntactical formats, such as PDF, Excel, CSV, XML, JSON or through direct database entry into custom systems. Each of these formats was designed and selected with principal requirements in mind. For example, for PDF, or Portable Document Format, the name is self-explanatory; while the format may be employed for other purposes, it is primarily meant to exchange documents reliably between computers. Quite often the reporting or data exchange requirements in a situation dictate the data format and systems involved.</div>
<div class="tdh_066">Unfortunately, many organizations and agencies today do not use a consistent data format either across agencies or even within a single organization. A data consumer receiving information in different formats must then use different methods to extract and use it. Furthermore, not all formats can be processed equally by computers. For example, a PDF document, though generally readable by people, is not guaranteed to contain textual information that can be parsed and interpreted by a computer. This makes using data in a PDF report and other formats difficult. The lack of structure among formats and systems tends to lead to an inability to gather, analyze, and collect information. One could take two PDF reports and note and compare their data, but this task becomes significantly more arduous when there are hundreds or thousands of reports to compare. In addition, the way in which one reporting entity expresses a data point may not be consistent with how other entities represent the same information. How can a data consumer relate information presented in such disparate manners?</div>
<div class="tdh_066">Corporate regulators have tackled this problem by introducing mandates requiring reporting entities to produce data using XBRL. Such mandates supply government officials and investors with well-structured and well-defined data that can be utilized in a variety of ways without the loss of meaning that is typically encountered when information is moved from one system to another.</div>
<div class="tdh_066">XBRL offers a wealth of information about data without cluttering each data point with unnecessary properties by using <i>taxonomies</i>, which are standardized documents that describe concepts and their relationships. Taxonomies can contain information as simple as geographic locations or as complex as United States General Accepted Accounting Principles (US GAAP) financial standards. XBRL data can also employ multiple taxonomies to bridge data across multiple sectors or industries. XBRL&#8217;s ability to &#8220;tag&#8221; unstructured data as well as traditional data makes it ideal for exchanging a wide variety of rich information between systems. When data is tagged in XBRL, the destination system knows to what the data applies, to what it relates, what time frame is being reported, the unit or language of numeric or textual data respectively, the type and precision of the data, and finally, what standard or rule is used to</div>
<p><!-- Field: Page; Sequence: 9 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->4<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">generate the data point. Also, because the XBRL format is self-describing, XBRL software can provide additional functionality, such as validation and mathematical comparisons, with little or no additional development when that format changes.</div>
<div class="tdh_066">While XBRL got its start by being used for compliance-related purposes, it is an extremely versatile data standard with applications only limited by the imagination of taxonomy architects.</div>
<p class="tdh_026">1.3.3.1     XBRL and Data Formats</p>  

<div class="tdh_066">The XBRL specification currently defines how data is captured and represented in a format originally based on XML. XML was selected as the starting point for XBRL because it is an excellent platform (with a wide array of tools and support) to carry complex data. XML is also a &#8220;markup language&#8221; that uses elements to tag and identify data points so a computer can easily process the data. Further, XML inherently allows contextual and other data to be included in each of those tags through the use of attributes. Interestingly, because XBRL is a data standard that establishes precepts rather than format, the vehicle for communicating the data could be based on other data formats like JSON. The benefits and disadvantages of data formats other than XML is discussed in Section 5.4.3. The fact that XBRL has flexibility in its transmission format makes it even more versatile as a reporting standard.</div>
<div class="tdh_066">Because XBRL taxonomies are XML-based but extend upon that foundation, changing information in a taxonomy does not necessitate the system reading and consuming the XBRL data to update to a new standard in order to understand its meaning. A system that reads XBRL can simply &#8220;plug in&#8221; new taxonomies as they become available without the need to change programmatically. This flexibility is unparalleled in a data exchange standard. When a real-world change would require a conceptual change to the meaning of data, a new version of the taxonomy can be created and released in response. Data consumers would have access to the new information in the same instant the taxonomy becomes available.</div>
<p class="tdh_026">1.3.3.2     Practical Applications and Success Stories</p>  

<div class="tdh_066">The XBRL standard is widely used for reporting around the world. Implementations include public and private company reporting as well as government agency reporting. Numerous government programs to report business financial information in XBRL exist globally (Table 1-1). One of the largest implementations of XBRL as a data transport method involving regulation is periodic financial reporting to the United States Securities and Exchange Commission (SEC). In this case, commonly used accounting standards were incorporated into financial reporting taxonomies. Now, using those taxonomies, public companies report required financial information through the Electronic Data Gathering, Analysis, and Retrieval (EDGAR) System. With XBRL, financial data is publicly available for machine-driven analysis and consumption with very little delay or overhead once the reports are filed. Banks reporting to the Federal Deposit Insurance Corporation (FDIC) represent another industry where XBRL serves as a successful transmission structure. Here, the taxonomy is very tightly regulated and used by multiple banks to report regulatory information to the FDIC. These are just two examples of successful implementations of XBRL in the fields of governmental regulation.</div>
<div class="tdh_066">XBRL provides a strong advantage for regulatory reporting, but its uses extend beyond the scope of regulatory disclosure. Perhaps one of the best business cases that can be made for XBRL is in collaborative settings. XBRL is an excellent solution for situations requiring a common interface among diverse businesses. An example is the development of the Work in Process (WIP) taxonomy for construction projects with long time horizons. Surety insurance companies that provide bonds for these projects require periodic reporting so they can judge whether the agreed upon timeline for completion is likely to be met and the loan repaid in a timely manner. There are many lenders and many developers in this collaborative setting. The developers all have similar reporting requirements to the lenders and the lenders all have similar needs for information about the status of construction projects. Developing an XBRL taxonomy in a situation like this allows the common information needs of the developers and lenders to be standardized and processed without human intervention.</div>
<div class="tdh_066">XBRL adds significant value in business cases where participants share a common set of information requirements among a subset of their business processing needs.</div>
<p><!-- Field: Page; Sequence: 10 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->5<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<table class="tdh_077" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td class="tdh_203"><span class="tdh_043"><b>Country</b></span></td>
<td class="tdh_203"><span class="tdh_043"><b>Application</b></span></td>
<td class="tdh_203"><span class="tdh_043"><b>Regulator</b></span></td>
<td class="tdh_203"><span class="tdh_043"><b>Apx. Reporting Entities</b></span></td>
</tr>
<tr>
<td class="tdh_207"><span class="tdh_043">United States</span></td>
<td class="tdh_207"><span class="tdh_043">Primary financials and disclosures for all public companies</span></td>
<td class="tdh_207"><span class="tdh_043">Securities and Exchange Commission (SEC)</span></td>
<td class="tdh_206"><span class="tdh_043">9,000</span></td>
</tr>
<tr>
<td class="tdh_211"><span class="tdh_043">United States</span></td>
<td class="tdh_211"><span class="tdh_043">Financial statements from all bank institutions</span></td>
<td class="tdh_211"><span class="tdh_043">Financial Depository Insurance Corporation (FDIC)</span></td>
<td class="tdh_210"><span class="tdh_043">8,500</span></td>
</tr>
<tr>
<td class="tdh_207"><span class="tdh_043">United Kingdom</span></td>
<td class="tdh_207"><span class="tdh_043">Financial statements from all private companies; tax filings</span></td>
<td class="tdh_207"><span class="tdh_043">Her Majesty&#8217;s Revenues &amp; Customs (HMRC) and Companies House</span></td>
<td class="tdh_206"><span class="tdh_043">2 million +</span></td>
</tr>
<tr>
<td class="tdh_211"><span class="tdh_043">Singapore </span></td>
<td class="tdh_211"><span class="tdh_043">Financial statements from all private companies</span></td>
<td class="tdh_211"><span class="tdh_043">ACRA (Accounting and Corporate Regulatory Authority) &#8211; BizFinx Filing system</span></td>
<td class="tdh_210"><span class="tdh_043">60,000</span></td>
</tr>
<tr>
<td class="tdh_207"><span class="tdh_043">Spain</span></td>
<td class="tdh_207"><span class="tdh_043">Financial statements from all private companies</span></td>
<td class="tdh_207"><span class="tdh_043">Business Registrar, Banking Regulator, Securities Regulation, Accounting Oversight and State Federal Comptroller</span></td>
<td class="tdh_206"><span class="tdh_043">800,000+</span></td>
</tr>
<tr>
<td class="tdh_211"><span class="tdh_043">Denmark</span></td>
<td class="tdh_211"><span class="tdh_043">Financial statements from all private companies</span></td>
<td class="tdh_211"><span class="tdh_043">Danish Business Authority/SKAT</span></td>
<td class="tdh_210"><span class="tdh_043">600,000</span></td>
</tr>
<tr>
<td class="tdh_207"><span class="tdh_043">South Korea</span></td>
<td class="tdh_207"><span class="tdh_043">Private and Listed Companies</span></td>
<td class="tdh_207"><span class="tdh_043">Financial Supervisory Service (FSS) and Korea Exchange (KRX)</span></td>
<td class="tdh_206"><span class="tdh_043">15,000</span></td>
</tr>
<tr>
<td class="tdh_211"><span class="tdh_043">Italy</span></td>
<td class="tdh_211"><span class="tdh_043">Financial statements from all private companies</span></td>
<td class="tdh_211"><span class="tdh_043">Infocamere/Unioncamere</span></td>
<td class="tdh_210"><span class="tdh_043">1 million</span></td>
</tr>
<tr>
<td class="tdh_207"><span class="tdh_043">Peru</span></td>
<td class="tdh_207"><span class="tdh_043">Banking and Insurance Regulation</span></td>
<td class="tdh_207"><span class="tdh_043">Superindencia de Banca y Seguros (SBS) and Superintendencia del Mercado del Valores (SMV)</span></td>
<td class="tdh_206"><span class="tdh_043">180</span></td>
</tr>
<tr>
<td class="tdh_211"><span class="tdh_043">Iran</span></td>
<td class="tdh_211"><span class="tdh_043">Listed Companies</span></td>
<td class="tdh_211"><span class="tdh_043">Securities and Exchange Organization</span></td>
<td class="tdh_210"><span class="tdh_043">300+</span></td>
</tr>
<tr>
<td class="tdh_207"><span class="tdh_043">Israel</span></td>
<td class="tdh_207"><span class="tdh_043">Listed Companies</span></td>
<td class="tdh_207"><span class="tdh_043">Israel Securities Authority</span></td>
<td class="tdh_206"><span class="tdh_043">600</span></td>
</tr>
<tr>
<td class="tdh_211"><span class="tdh_043">Japan</span></td>
<td class="tdh_211"><span class="tdh_043">Listed Companies</span></td>
<td class="tdh_211"><span class="tdh_043">Japan Financial Services Agency (JFSA)</span></td>
<td class="tdh_210"><span class="tdh_043">9,000</span></td>
</tr>
<tr>
<td class="tdh_207"><span class="tdh_043">Belgium</span></td>
<td class="tdh_207"><span class="tdh_043">Financial statements from all private companies</span></td>
<td class="tdh_207"><span class="tdh_043">National Bank of Belgium (Central Balance Sheet Office)</span></td>
<td class="tdh_206"><span class="tdh_043">400,000</span></td>
</tr>
<tr>
<td class="tdh_211"><span class="tdh_043">Panama</span></td>
<td class="tdh_211"><span class="tdh_043">Banking and insurance regulation</span></td>
<td class="tdh_211"><span class="tdh_043">SBP (Superintendencia de Bancos de Panama &#8211; Superintendency of Banks</span></td>
<td class="tdh_210"><span class="tdh_043">76</span></td>
</tr>
<tr>
<td class="tdh_207"><span class="tdh_043">Germany</span></td>
<td class="tdh_207"><span class="tdh_043">Financial statements from all private companies</span></td>
<td class="tdh_207"><span class="tdh_043">Bundensanzeiger</span></td>
<td class="tdh_206"><span class="tdh_043">1 million</span></td>
</tr>
<tr>
<td class="tdh_211"><span class="tdh_043">Chile</span></td>
<td class="tdh_211"><span class="tdh_043">Banking and insurance regulation</span></td>
<td class="tdh_211"><span class="tdh_043">Superintendencia de Valores y Seguros (SVS)</span></td>
<td class="tdh_210"><span class="tdh_043">270</span></td>
</tr>
<tr>
<td class="tdh_207"><span class="tdh_043">Taiwan</span></td>
<td class="tdh_207"><span class="tdh_043">Securities regulation</span></td>
<td class="tdh_207"><span class="tdh_043">Taiwan Stock Exchange</span></td>
<td class="tdh_206"><span class="tdh_043">1500</span></td>
</tr>
<tr>
<td class="tdh_211"><span class="tdh_043">Brazil</span></td>
<td class="tdh_211"><span class="tdh_043">Public spending</span></td>
<td class="tdh_211"><span class="tdh_043">National Treasury</span></td>
<td class="tdh_212">
<p class="tdh_101">Federal government</p>  

<p class="tdh_101">26 States</p>  

<p class="tdh_101">5570 municipalities</p>  

</td>
</tr>
<tr>
<td class="tdh_209"><span class="tdh_043">Colombia</span></td>
<td class="tdh_209"><span class="tdh_043">Financial statements from businesses and financial institutions</span></td>
<td class="tdh_209"><span class="tdh_043">Superintendencia de Sociedades; Superintendencia Financiera de Colombia</span></td>
<td class="tdh_208"><span class="tdh_043">1000+</span></td>
</tr>
<tr>
<td class="tdh_211"><span class="tdh_043">World Bank</span></td>
<td class="tdh_211"><span class="tdh_043">Sustainability Reporting</span></td>
<td class="tdh_211"><span class="tdh_043">Internal Report</span></td>
<td class="tdh_210"><span class="tdh_043">1</span></td>
</tr>
<p><!--


<tr>


<td class="tdh_235">&nbsp;</td>




<td class="tdh_241">&nbsp;</td>




<td class="tdh_249">&nbsp;</td>




<td class="tdh_256">&nbsp;</td>




<td class="tdh_246">&nbsp;</td>




<td class="tdh_235">&nbsp;</td>


</tr>


--></tbody>
</table>
<p class="tdh_106"><a name="a_Ref16495140"></a>Table 1-1. Examples of successful XBRL implementations worldwide</p>  

<div class="tdh_066">XBRL taxonomies can serve large industries, projects, and data sets, but they can also prove useful in smaller settings. Departments within a company or university may need to report to each other in a structured, predictable manner, for example. XBRL is well suited for business and financial data, but it</div>
<p><!-- Field: Page; Sequence: 11 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->6<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">need not be limited to this application. Taxonomies can be constructed to reflect any type of information, and XBRL&#8217;s strengths in structured reporting can benefit any situation where data integrity and semantic interpretability is essential.</div>
<div class="tdh_027"><a name="a_Toc24107528"></a><a name="a_Toc23337674"></a>1.4   What Is in this Document</div>
<div class="tdh_066">This document contains information that helps readers understand XBRL and its potential applications. It will walk readers through building an XBRL taxonomy. It begins with information to help readers understand data modeling (and how data modeling translates to XBRL) and define the needs of the project. It continues by discussing the mechanics of building and implementing the taxonomy. Finally, this document explores governing the reporting system afterward. The manual builds a story that is the creation of an XBRL taxonomy from cover to cover, but sections or chapters can be skipped or read selectively without loss of continuity.</div>
<div class="tdh_066"><b>Chapter 1 — Introduction</b> — A synopsis of the <i>Taxonomy Development Handbook</i> and XBRL.</div>
<div class="tdh_066"><b>Chapter 2 — An Introduction to XBRL</b> — An overview of XBRL and its principals and conventions. Within this introduction is a general discussion of how XBRL is different than other data exchange standards such as basic XML, JSON or CSV.</div>
<div class="tdh_066"><b>Chapter 3 — Structuring Data</b> — A discussion of methods for organizing data within an instance and the options for structuring dimensional data.</div>
<div class="tdh_066"><b>Chapter 4 — Assessing Overall Project Scope</b> — A discussion of how stakeholders and use cases affect the data model.</div>
<div class="tdh_066"><b>Chapter 5 — Building a Transport Data Model</b> <i>— </i>An in-depth review of taking the XBRL data model and applying stakeholder needs to create an XBRL transport model.</div>
<div class="tdh_066"><b>Chapter 6 — The Mechanics of Taxonomy Development </b>— Detailed instructions on building a taxonomy in XML.</div>
<div class="tdh_066"><b>Chapter 7 — Documenting a Taxonomy</b> — A discussion of how to document a taxonomy for use by preparers, developers, and information consumers.</div>
<div class="tdh_066"><b>Chapter 8</b> <b>—</b> <b>Taxonomy Governance</b> — Directions for the on-going maintenance of an implemented taxonomy.</div>
<div class="tdh_066"><b>Chapter 9 — Success Stories </b>— A review of real-world implementations of XBRL.</div>
<div class="tdh_066"><b>Appendix A — XBRL and XML Supporting Information</b> — A collection of technical information to aid in understanding and using XBRL.</div>
<div class="tdh_066"><b>Appendix B — Taxonomy Creation Checklist</b> — A basic checklist of &#8220;to do&#8221; items for creating a taxonomy.</div>
<div class="tdh_066"><b>Appendix C — <i>Taxonomy White Paper</i> Outline and Template</b> <i>— </i>Information to aid in the creation of a project &#8220;white paper&#8221; to aid in the process of developing a taxonomy.</div>
<div class="tdh_066"><b>Appendix D — <i>XBRL Overview</i> Template</b> <i>—</i> An example <i>XBRL Overview</i> section to be included in taxonomy documentation.</div>
<div class="tdh_066"><b>Appendix E — <i>Taxonomy Guide</i> Outline and Template</b> <i>— </i>An outline for a consolidated <i>Taxonomy Guide</i> to be used by users of a taxonomy including preparers, consumers and software developers.</div>
<div class="tdh_066"><b>Appendix F — <i>Preparer Guide</i> Outline and Template </b>— An outline for a separate <i>Preparer Guide</i> aimed to aid preparers in using the developed taxonomy.</div>
<div class="tdh_066"><b>Appendix G — <i>Data Consumer Guide</i> Outline and Template </b>— An outline for a separate <i>Data Consumer Guide</i> aimed to demonstrate to data consumers how the information in the taxonomy can be applied to common use cases.</div>
<p><!-- Field: Page; Sequence: 12 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->7<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066"><b>Appendix H — XBRL US Taxonomy Approval Metrics</b> — Information as to how a taxonomy can be reviewed and approved by XBRL US.</div>
<div class="tdh_066"><b>Appendix I — Intellectual Property Status </b>— An overview of Intellectual Property considerations and a sample IP statement.</div>
<div class="tdh_066"><b>Appendix J — Document Revision Status </b>— A discussion of the status of the <i>Taxonomy Development Handbook</i>, including pertinent revisions.</div>
<div class="tdh_066"><b>Appendix K — Revisions and Public Comments </b>— A discussion of public comments and the relevant revisions.</div>
<div class="tdh_066"><b>Glossary — </b>A glossary of terms used for XBRL and within this document.</div>
<p class="tdh_020"><span class="tdh_024">1.4.1     </span>Supporting Specifications</p>  

<div class="tdh_066">This document is <i>not</i> a specification but rather a guide to aid in the development of well-formed taxonomies as well as setting forth best practices in development and management.</div>
<div class="tdh_066">The following documentation was relied upon during the development of this guide. Readers are encouraged to both become familiar and comply with the following documents:</div>
<p class="tdh_063"><a href="https://specifications.xbrl.org/work-product-index-group-base-spec-base-spec.html"><span class="tdh_035"><i><u>Extensible Business Reporting Language (XBRL) Specification</u></i></span></a> — The <i>Extensible Business Reporting Language Specification</i>, from XBRL International (XII), contains the raw information regarding the implementation of XBRL in XML. It defines XML elements and attributes that can be used to express information used in the creation, exchange, and comparison tasks of business reporting. Note that the XBRL specification terminology is XML centric.</p>  

<p class="tdh_063"><a href="http://www.xbrl.org/Specification/oim/CR-2019-06-12/oim-CR-2019-06-12.html"><span class="tdh_035"><i><u>XBRL Open Information Model</u></i></span></a> — The <i>Open Information Model</i> (OIM) describes methods of relaying XBRL information in a syntax independent manner focusing on JSON (JavaScript Object Notation) and CSV (Comma Separated Values) while revising some of the terminology to work in such environments. The OIM specification is supplied with companion examples and documents.</p>  

<p class="tdh_063"><a href="http://www.xbrl.org/specification/dimensions/rec-2012-01-25/dimensions-rec-2006-09-18+corrected-errata-2012-01-25-clean.html"><span class="tdh_035"><i><u>XBRL Dimensions Specification</u></i></span></a> — The <i>XBRL Dimensions Specification</i> provides a generalized mechanism to define dimensional metadata and to reference it in XBRL instances. It defines an architecture such that any XBRL artefacts (instances and their Discoverable Taxonomy Sets) that conform to the specification may be processed without error by any processor that is capable of correctly processing XBRL artefacts, even if those processors are unaware of modular extension.</p>  

<p class="tdh_063"><a href="https://specifications.xbrl.org/work-product-index-registries-dtr-1.0.html"><span class="tdh_035"><i><u>XBRL Data Type Registry</u></i></span></a> — The <i>XBRL Data Type Registry</i> (DTR) contains the data types defined by XBRL. These are in addition to standard XML data types. In addition, there are two provided specifications, the Process Specification and Structure Specification, which further describe the structure of the DTR and the steps through which a new data type can be added to it.</p>  

<p class="tdh_063"><a href="https://specifications.xbrl.org/release-history-base-spec-pdu.html"><span class="tdh_035"><i><u>XBRL Precision, Decimals and Units</u></i></span></a> <span class="tdh_035"><i><u>Specification</u></i></span> — The <i>XBRL Precision, Decimals and Units Specification</i> details more information relating to the numerical precision, decimal expression, and units of XBRL facts (the @precision and @decimals fact attributes). This document extends the information provided in the <a href="https://specifications.xbrl.org/work-product-index-group-base-spec-base-spec.html"><span class="tdh_035"><i><u>XBRL Specification</u></i></span></a> and also offers more examples of conventions used in practice.</p>  

<p class="tdh_063"><a href="https://specifications.xbrl.org/work-product-index-formula-formula-1.0.html"><span class="tdh_035"><i><u>XBRL Formula</u></i></span></a> <span class="tdh_035"><i><u>Specification</u></i></span> — The <i>XBRL Formula Specification</i> describes methods of providing additional validation that is not provided by the base <a href="https://specifications.xbrl.org/work-product-index-group-base-spec-base-spec.html"><span class="tdh_035"><i><u>XBRL Specification</u></i></span></a> through XBRL formulas. The specification explains methods of using formulas and other approaches to test rigorously the data relationships within an instance document.</p>  

<p class="tdh_063"><a href="https://specifications.xbrl.org/work-product-index-registries-units-registry-1.0.html"><span class="tdh_035"><i><u>XBRL Units Registry</u></i></span></a> — Similar to the <a href="https://specifications.xbrl.org/work-product-index-registries-dtr-1.0.html"><span class="tdh_035"><i><u>XBRL Data Types Registry</u></i></span></a>, the <i>XBRL Units Registry</i> (UTR) defines the XBRL-allowable units for numeric facts. There is further documentation concerning the structure and syntax of the registry as well as information on the process by which new units can be added.</p>  

<p><!-- Field: Page; Sequence: 13 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->8<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_063"><a href="https://specifications.xbrl.org/work-product-index-inline-xbrl-transformation-registry-3.html"><span class="tdh_035"><i><u>XBRL Transformation Registry</u></i></span></a>— The <i>XBRL Transformation Registry</i> contains the rules and metrics by which transformations in Inline XBRL are performed. These rules describe how descriptive text in Inline XBRL documents can be represented as XBRL data types.</p>  

<p class="tdh_020"><span class="tdh_024">1.4.2     </span>Supporting Documents</p>  

<div class="tdh_066">Other documents important to taxonomy development include:</div>
<p class="tdh_063"><a href="https://xbrl.us/wp-content/uploads/2017/09/style-guide-20170907.pdf"><span class="tdh_035"><i><u>XBRL US Style Guide</u></i></span></a> — The <i>XBRL US Style Guide</i> aids in maintaining consistency in all aspects of XBRL, including style, as a critical component to the successful deployment the XBRL taxonomies. The guide lays out goals to: (a) provide a basis for the consistent development and maintenance of taxonomies; (b) increase the efficiency and effectiveness of taxonomies; (c) improve taxonomy extensibility for end users and taxonomy developers; (d) maximize comparability of data, reduce the ambiguity of data, and promote the normalization of data; (e) increase compatibility of taxonomies; (f) improve the reliability and consistency of the concepts, labels and documentation; and, (g) reduce the cost of taxonomy implementation.</p>  

<p class="tdh_063"><a href="https://xbrl.us/xbrl-reference/tam/"><span class="tdh_035"><i><u>XBRL US Taxonomy Approval Metrics</u></i></span></a> — The <i>Taxonomy Approval Metrics</i> (TAM) document establishes standards for XBRL taxonomy review and approval by the XBRL US Domain Steering Committee (DSC) with the following goals: (a) to enable a meaningful exchange of information between two different business systems; (b) to avoid confusion and difficulties in initial setup of systems for the preparation and consumption of XBRL-based information; (c) to provide Developers with a clear understanding of the expectations of the requirements of the XBRL US Domain Steering Committee (DSC) Taxonomy Approval Process.</p>  

<p class="tdh_020"><span class="tdh_024">1.4.3     </span>Supporting Software and Tools</p>  

<div class="tdh_066">There are various freely available software packages and tools that can aid in taxonomy development and XBRL instance document preparation or data extraction. They are as follows:</div>
<p class="tdh_063"><a href="http://arelle.org/"><span class="tdh_035"><i><u>Arelle</u></i></span></a> — Arelle is an open source platform for XBRL that can be used as a desktop application and integrated with other applications and languages through its web service. Numerous plugins exist to allow interfacing with Excel, Java, Oracle, RSS feeds, and individual XBRL documents, and SQL and other databases. Arelle is covered in more detail in Chapter 6 as a means visualize and facilitate taxonomy development.</p>  

<p class="tdh_063"><i>XBRL API</i> — Developed by XBRL US, the XBRL API (Application Program Interface) aids users in accessing timely, structured XBRL data with high resolution. The standardized API allows developers and data utilities to employ a single interface to gather data from an XBRL repository/instance. Developers can use the API to connect a custom database to a software front end. The API aids in automatically populating that database and permitting users to gather it for analysis.</p>  

<p class="tdh_063">More information about the XBRL API is available on XBRL US&#8217; website and in the API documentation (<a href="http://files.xbrl.us/documents/XBRL-API-V1.4.pdf"><span class="tdh_035"><i><u>http://files.xbrl.us/documents/XBRL-API-V1.4.pdf</u></i></span></a>).</p>  

<p class="tdh_063"><i>Spreadsheet/Word-processing Applications</i> — There are numerous free software packages that offer spreadsheet and word-processing capabilities. These basic utilities can aid in drafting project plans and documentation as well as creating the taxonomy itself. In conjunction with Arelle, spreadsheets can be used to lay out the elements of the taxonomy in a human-readable, well organized manner. Free applications are offered at:</p>  

<ul>
<li><span class="tdh_190">Google Docs (<a href="http://docs.google.com/"><span class="tdh_035"><i><u>http://docs.google.com/</u></i></span></a>)</span></li>
<li><span class="tdh_190">LibreOffice (<a href="http://www.libreoffice.org/"><span class="tdh_035"><i><u>http://www.libreoffice.org/</u></i></span></a>)</span></li>
<li><span class="tdh_190">Microsoft Office Online (<a href="http://www.office.com/"><span class="tdh_035"><i><u>http://www.office.com/</u></i></span></a>)</span></li>
</ul>
<p class="tdh_063">Note that XBRL US does not endorse any of these products, and some may require valid accounts with the provider to use. In addition, some functionality may require purchase. XBRL US has a list of some XBRL software vendors on its website at <a href="https://xbrl.us/"><span class="tdh_035"><i><u>https://xbrl.us/</u></i></span></a>.</p>  

<p><!-- Field: Page; Sequence: 14 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->9<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt; float: right; margin: 8px; border: 1px solid #e2e2e2; border-bottom: none;"><a href="#toc">Table of Contents</a></div>
<div class="tdh_028"><a name="a_Toc24107529"></a><a name="a_Toc23337675"></a><a name="a_Ref19622727"></a><a name="a_Toc15912824"></a><a name="a_Toc15912887"></a>2   An Introduction to XBRL</div>
<div class="tdh_027"><a name="a_Toc24107530"></a><a name="a_Toc23337676"></a>2.1   eXtensible Business Reporting Language</div>
<p class="tdh_020"><span class="tdh_024">2.1.1     </span>Why XBRL</p>  

<div class="tdh_066">XBRL was developed to automate the process of sharing information within an organization and with external regulators, markets, and non-governmental organizations. Conceptual requirements for XBRL development included creating a system that is extensible, definable, and one that allows for comparisons of its data. XBRL also had to possess the ability to hold or transport a wide variety of data, support standardized data representations, and be software agnostic such that the standards can be used through many different software applications.</div>
<div class="tdh_066">XBRL principally serves as a method that simultaneously transmits machine-readable data with information about how to interpret and contextualize that data. This is in contrast to other data transmission methods, where a single point of data is often bereft of further information to enhance or elucidate it. Using XBRL as a data structure ensures properly tagged points of data will be interpreted by the receiving system with all the meaning required to interpret that data, regardless of the originating system, time of interpretation, or the method of transmission. In data architecture, this is referred to as <i>semantic interoperability</i>. Semantic interoperability is achieved through adding information that links each data element to a well-defined, shared vocabulary among the systems. This creates an information package that is self-describing and therefore independent of its originating information system and capable of being read by any destination system. Underlying semantic interoperability is <i>syntactic interoperability</i>, which is the syntax by which two or more systems communicate with each other, coupled with a defined ontology, which must be able to adapt to new and changing terms. XBRL provides the foundation for these two important facets of relaying data: a <i>syntactical specification</i> relying on common standards to convey information and a means of providing an <i>ontology</i> (an XBRL taxonomy) to identify the meaning of that information within a well-defined semantic framework (Figure 2-1).</div>
<p class="tdh_099"><img class="tdh_142" src="http://files.xbrl.us/images/tdh/tdh_p1_003.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref16068932"></a>Figure 2-1. XML as the syntactic component of XBRL and the XBRL taxonomy as a semantic framework</p>  

<div class="tdh_066">There are many standards for formatting, transmitting, storing, and presenting information, and each is designed for a specific purpose. Unlike many other data standards, XBRL allows for the simultaneous conveyance of structure and meaning, and its ontology can be adapted to suit a broad range of purposes and industries. This handbook examines how XBRL can become an integral part of a data architecture solution.</div>
<p class="tdh_020"><span class="tdh_024">2.1.2     </span>The Transport Data Model</p>  

<div class="tdh_066">The task of an XBRL taxonomy developer is to take a semantic data model that represents business or other data and build a transport model to proliferate that data to data consumers. A <i>transport model</i></div>
<p><!-- Field: Page; Sequence: 15 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->10<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">serves as an organizational structure when moving data from a source to a consumer (Figure 2-2). XBRL is an example of a transport model. Transport models can be complex and dynamic, such as XBRL, or they can be simple. In a sense, the act of filling out a paper or electronic form that contains fields for sets of information creates a transport model. The form takes data from a preparer in an organized way and then allows consumers to use that data as necessary. Of course, there can be very obvious limitations to a form-based transport model, such as the fact that the form may not be machine-readable, but this illustrates the concept that the model is the format that allows data to move from a source to a consumer in a meaningful way.</div>
<p class="tdh_099"><img class="tdh_132" src="http://files.xbrl.us/images/tdh/tdh_p1_004.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref5875748"></a><a name="a_Ref5875815"></a>Figure 2-2. An XBRL taxonomy as a transport data model</p>  

<div class="tdh_066">In a real-world environment, a reporting entity may use a variety of applications to manage and store business data. Such data can contain customer/client information, products, inventory, research, accounting, and modeling information. From an information technology standpoint, data points should fit into an ideal <i>semantic model</i>, where the dimensionality of that model provides a self-describing data set even though segments may exist in separate systems on separate platforms. In most cases, not all information from the semantic model is placed in the transport model for a variety of reasons ranging from confidentiality, depth or history of information, or the data simply not being required. In addition, some data points in the transport model may need to be created or calculated from points within the semantic model. As a result, the data from the semantic model must be filtered or prepared.</div>
<div class="tdh_066">Transport models can also be thought of as a link in an <i>information supply chain</i>. This supply chain refers to the systems of organizations, people, resources, and processes in moving data from a source (a business or semantic data model) to a consumer. Supply chains can be very complicated, involving multiple parties and models of information, or they can be simple. It is also important to note that in Figure 2-2, the business data and semantic model will vary from reporting entity to reporting entity, while the transport model will remain the same for all reporting entities. Also, the transport model may or may not match either the source (semantic) model or the <i>consumer model</i>. The challenge for developers is to create a transport model that is closely aligned with all the stakeholder requirements and is still easy to understand and expand to accommodate future requirements.</div>
<div class="tdh_066">XBRL provides the format of the transport model, and an <i>XBRL report</i> contains the information that is being exchanged among systems using that transport model. The defining and unifying force behind the structured XBRL transport model is the <i>taxonomy</i>. With a well-defined taxonomy, any consumer of data within an XBRL report should be able to properly read and interpret that data.</div>
<div class="tdh_066">The right side of Figure 2-2 is the consumer model. Consumers may take various forms and can have widely varying requirements. Each will have their own specific models and may combine data from other sources to support their end work product. Consumers represent important stakeholders in the</div>
<p><!-- Field: Page; Sequence: 16 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->11<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">development process, and their needs concerning the way in which the reported data is organized should be considered.</div>
<div class="tdh_066">Note that Figure 2-2 is silent on the actual mechanics of transmitting and storing data, which is beyond the scope of this document. Suffice it to say, however, taxonomy developers may be tasked with determining how data will be moved and stored. In some cases, the process may be a secure private transaction from party to party, while in others, such as the SEC&#8217;s EDGAR system, the data is private until accepted by a regulatory system and then stored in a publicly available archive.</div>
<p class="tdh_026">2.1.2.1     XBRL as a Transport Model</p>  

<div class="tdh_066">XBRL provides a standard set of rules that define how data (which can be a broad range of types, including monetary, integer, text, and Boolean) can be transported. As mentioned previously, an XBRL report, also called an <i>instance document</i>, serves as the transmission or storage vehicle for the data reported. An XBRL taxonomy dictates how the data in that report should be organized. The taxonomy can only be built in XML, but the taxonomy can be used to generate XBRL instance documents in XML, JSON, HTML (Inline XBRL), or CSV format. XBRL International, which directs the ongoing development of the <a href="https://specifications.xbrl.org/work-product-index-group-base-spec-base-spec.html"><span class="tdh_035"><i><u>XBRL Specification</u></i></span></a>, has created XBRL versions of these formats which are capable of intrinsically carrying semantic information along with the reported values.</div>
<div class="tdh_066">The four format options for an XBRL instance document are as follows:</div>
<p class="tdh_064"><i>XBRL as XML</i> — In this mode, instance data is stored in XML format as dictated by the <a href="https://specifications.xbrl.org/work-product-index-group-base-spec-base-spec.html"><span class="tdh_035"><i><u>XBRL Specification</u></i></span></a>. XML provides for the construction of custom schema to express a wide range of data types using elements to delineate and &#8220;markup&#8221; data. XBRL builds on XML by adding relationships beyond simple parent-child inheritance as well as additional contextual information. Additional linkbases can be provided for definitions, references, labels, calculations, and presentations.</p>  

<p class="tdh_064"><i>Inline XBRL</i> — Inline XBRL (iXBRL) allows the instance data to be embedded in an XHTML document. This is iXBRL&#8217;s principal advantage, that machine readable data is located right within the human readable report. A major advantage of this method is that preparers can be less concerned about the presentation aspect of the XBRL data. Schema and linkbase requirements are the same as with XML.</p>  

<p class="tdh_064"><i>JSON</i> — JSON, or JavaScript Object Notation, is a text format that provides for the expression of complex structured data. A number of programming languages will natively create and read JSON. For XBRL, the Open Information Model (OIM)<a class="tdh_040" href="#note_ftn1" name="note_ftnref1">1</a>, which is a syntax-independent model of XBRL data developed by XBRL International, provides a specification for storing instance information in an XBRL-JSON report. JSON only allows for the transport of instance information. If extensions are allowed in the instance document and JSON is used, a schema (extension taxonomy) must be created in XML to accompany the JSON file.</p>  

<p class="tdh_064"><i>CSV</i> — CSV (Comma Separated Values or comma delimited) is another option for transport. However, given the limited structure of CSV, files must be formatted in a specific manner with companion information to connect key XBRL structural data. CSV can be a good option for reporting highly structured information where only the facts change from report to report. The Open Information Model (OIM) provides a specification for storing instance information in an XBRL-CSV report. As with JSON, if extensions are needed, a schema (extension taxonomy) must be created in XML to accompany the CSV file.</p>  

<div class="tdh_066">The format used for the instance document is up to the preparer of the information and/or the application selected. Other formats, at this time, do not have the structure to carry semantic information, without which the reported values cannot be automatically understood and consumed.</div>
<hr class="tdh_260" align="left" size="1" />
<p class="tdh_073"><a class="tdh_040" href="#note_ftnref1" name="note_ftn1">1</a> XBRL International Open Information Model: <a href="https://specifications.xbrl.org/work-product-index-open-information-model-open-information-model.html"><span class="tdh_035"><i><u>https://specifications.xbrl.org/work-product-index-open-information-model-open-information-model.html</u></i></span></a></p>  

<p><!-- Field: Page; Sequence: 17 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->12<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">A key feature of XBRL is the fact that it is <i>extensible</i>. This means the developers and/or regulators can permit preparers to extend the taxonomy through the creation of custom data elements or organizational schemes. In a <i>closed</i> architecture, taxonomy developers allow preparers to transmit only the instance data. If the taxonomy is <i>open</i> and extensible by preparers, then an XML schema (extension taxonomy) must also be supplied. Extensibility is discussed in depth in Section 3.6.</div>
<p class="tdh_020"><span class="tdh_024">2.1.3     </span>Bringing Meaning to Data Points</p>  

<div class="tdh_066">Information can be gathered and organized in text, tables, named variables, arrays, and through other methods. However, with many of these methods, each reported value lacks additional identifying characteristics. In addition, depending on the language and platform, there may be varying data types or naming conventions. This can all lead to confusing comparisons among different data sets and to difficulties in transmitting the information from system to system.</div>
<p class="tdh_099"><img class="tdh_123" src="http://files.xbrl.us/images/tdh/tdh_p1_005.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref5875932"></a>Figure 2-3. Disorganized versus organized data</p>  

<div class="tdh_066">The goal of XBRL is to transport data that is arranged in a meaningful way. Data can be organized in an appropriate pattern depending on the application as tables, cubes, or perhaps in a <i>hierarchical structure</i>, for example (Figure 2-3). Each data point in an originating semantic data model may have a relationship with other data points that is demonstrative of its semantic meaning. XBRL adds depth to data points by adding <i>XBRL dimensions </i>to them. XBRL dimensions define the data&#8217;s semantic meaning, its periodicity, its reporting entity, and other descriptive information. Taken together, a data set&#8217;s dimensions represent meaningful semantic information and help consumers understand not only what each individual point means but how all the points within the set relate to each other.</div>
<div class="tdh_066">Beyond the representation of structured data, XBRL also offers several important features. First, data can be represented in a human readable form either as a structured presentation or as part of an HTML document text as <i>Inline XBRL</i> or <i>iXBRL</i>. Second, additional information can be conveyed both for specific data points and for relationships. For example, a data point can convey information about the type of data or its precision or it can have a textual note attached. In addition, XBRL is self-describing, meaning the taxonomy itself instructs receiving systems how to read and interpret the data structure. There is no need for additional libraries, documents, or formats. XBRL is also extensible, which allows both developers to build upon pre-existing taxonomies and preparers to create their own XBRL constructs to reflect their specific reporting circumstances (if permitted by developers). Finally, XBRL has multiple methods of enforcing and encouraging data integrity and validation. These topics will be addressed throughout this handbook to allow developers to leverage XBRL&#8217;s many strengths in their reporting solutions.</div>
<p><!-- Field: Page; Sequence: 18 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->13<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_027"><a name="a_Toc24107531"></a><a name="a_Toc23337677"></a>2.2   How Does XBRL Represent Data?</div>
<p class="tdh_020"><span class="tdh_024">2.2.1     </span>Overview</p>  

<div class="tdh_066">This section focuses on the basic structure of XBRL and how its constructs represent data points and their semantic dimensionality. Consider a simple report of monthly expenses, which may appear in a spreadsheet as follows:</div>
<p class="tdh_099"><img class="tdh_131" src="http://files.xbrl.us/images/tdh/tdh_p1_006.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref24622385"></a><a name="a_Ref5876018"></a>Figure 2-4. A simple expense example</p>  

<div class="tdh_066">On the left of Figure 2-4, there are categories of expenses (Column A, conventionally considered line items). Expense categories include Food, Entertainment, Fuel, Rent, and so forth. The types of expenses are reported by the month in which the expense occurred (Columns B-E). The data points appear at the intersection of the category and the month. By themselves, the values of these data points have very little meaning, but when taken in relationship to the row and column orientation, each field has meaning. This is a very typical, simple, tabular representation of data, where the data points are defined by a conceptual idea and a contextual timeframe to which that value pertains. In XBRL, this combination of a data point and a set of XBRL dimensions pertaining to that data point is called a fact.</div>
<p class="tdh_020"><span class="tdh_024">2.2.2     </span>The Fact (An Intersection of Dimensions and Data)</p>  

<div class="tdh_066"><a name="c2_fact"></a>In XBRL, a <i>fact</i> is the unique intersection of a set of <i>XBRL dimensions</i> with a data point. Figure 2-5 illustrates the basic structure of a fact. Arbitrary information, such as a number or a name or even a short section of text, has no semantic or contextual information in and of itself. Once XBRL dimensions, which add semantic information, intersect with that data point, it now becomes an XBRL fact.</div>
<p class="tdh_099"><img class="tdh_110" src="http://files.xbrl.us/images/tdh/tdh_p1_007.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref5882386"></a>Figure 2-5. A data point versus an XBRL fact</p>  

<div class="tdh_066">The data value can be of almost any form. For example, if data pertains to the number of widgets produced by a widget manufacturing company, it would be a numeric value. If the data was a narrative description of widget production challenges, it would be textual.</div>
<div class="tdh_066">In the simple expense example (Figure 2-4), the expense for Clothing in the context of January, which has a value of 180, is a fact. There are also implicit dimensions, some of which appear in Figure 2-6. These are monetary values, so the units could be US Dollars. These are also Bob&#8217;s expenses, so the</div>
<p><!-- Field: Page; Sequence: 19 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->14<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">reporting entity for that data point can be identified. All of these dimensions intersect at this fact, and the combination of the concept and the dimensions help define and dictate the nature of the information stored at that intersection. Facts must have a concept core dimension, which provides the semantic meaning of the fact. In this example, ClothingExpenses is the concept core dimension. A fact may also have other dimensions.</div>
<p class="tdh_099"><img class="tdh_140" src="http://files.xbrl.us/images/tdh/tdh_p1_008.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref8304984"></a><a name="a_Ref22644981"></a>Figure 2-6. The expense example with an illustrated XBRL fact</p>  

<div class="tdh_066">Figure 2-7 illustrates the intersection of the concept dimension and another XBRL dimension, defining a fact&#8217;s group of semantic dimensions. Again, relating to the expense example, the dimension is the period dimension January and the concept core dimension is ClothingExpenses.</div>
<p class="tdh_099"><img class="tdh_112" src="http://files.xbrl.us/images/tdh/tdh_p1_009.jpg" alt="A screenshot of a cell phone Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref5876107"></a>Figure 2-7. XBRL fact intersection with dimensions</p>  

<p><!-- Field: Page; Sequence: 20 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->15<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Multiple concepts along the concept dimension can intersect with the same secondary dimension (as shown in Figure 2-8). Looking back to the expense example, including multiple line item concepts adds a simple level of dimensionality to the data. A set of concepts (such as FoodExpenses, RentExpenses, ClothingExpenses, and UtilitiesExpenses) that intersect with a single period dimension (January) could be visualized as follows:</div>
<p class="tdh_065"><img class="tdh_130" src="http://files.xbrl.us/images/tdh/tdh_p1_010.jpg" alt="A close up of a device Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref5881634"></a>Figure 2-8. Multiple facts created by multiple concepts intersecting with one XBRL dimension</p>  

<div class="tdh_066">Again, this is analogous to line items on a table or spreadsheet with the data dimensionality expressed as the column heading. When there are multiple reporting periods (for example, for the first two months of expenses), multiple XBRL dimensions are defined, such as in Figure 2-9.</div>
<p class="tdh_099"><img class="tdh_139" src="http://files.xbrl.us/images/tdh/tdh_p1_011.jpg" alt="A close up of a map Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref5881721"></a>Figure 2-9. Multiple concepts and XBRL dimensions intersecting to form multiple facts</p>  

<div class="tdh_066">In this case, the concepts would be the line items in Figure 2-4 (such as Food Expenses, Rent Expenses, and Utilities Expenses). The periods would be represented by the columns (January, February, and so forth). Again, the places where each concept dimension and period dimension intersect is a fact (a monetary amount in this case, located in the cells), and the combination of the contextual information provided by the concept and other dimensions (the period) create the XBRL dimensions of that fact. This example illustrates the relationship among dimensions using the concept core dimension, period dimensions, and facts.</div>
<p class="tdh_020"><span class="tdh_024">2.2.3     </span>Dimensions</p>  

<div class="tdh_066"><a name="c2_dimension"></a>As mentioned previously, an <i>XBRL dimension</i> is information that serves to uniquely identify a fact (Figure 2-5). A dimension may be either a core dimension, which includes the concept core dimension, period</div>
<p><!-- Field: Page; Sequence: 21 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->16<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">core dimension, reporting entity core dimension, and unit core dimension, or a taxonomy-defined dimension. These are discussed in greater detail later in this chapter.</div>
<div class="tdh_066">Each XBRL dimension adds unique contextual information to a data point. The concept core dimension confers basic semantic meaning to a data point, such as FoodExpenses or FuelExpenses as shown in the earlier examples. Within an instance, similar dimensions intersect facts to form tables, cubes, or more complex structures. Each intersecting fact is always unique.</div>
<div class="tdh_066">There may also be, and often are, multiple dimensions associated with one fact. For example, in the expense data set, the columns represent period dimensions, and, as stated earlier, the rows could be considered concept core dimensions. These together are the dimensions for any given fact.</div>
<div class="tdh_066">Facts can have one or more of the following dimensions: the <i>concept core dimension</i>, the <i>entity core dimension</i>, the <i>period core dimension</i>, the <i>unit core dimension</i>, the <i>language core dimension</i>, the <i>note ID core dimension</i>, and <i>taxonomy-defined dimensions</i>.</div>
<p class="tdh_026">2.2.3.1     Concept Core Dimension</p>  

<div class="tdh_066">Every fact must have a concept core dimension as defined in Section 2.2.5. The concept core dimension provides semantic meaning for a fact. It also defines certain properties about the facts associated with it, including a fact&#8217;s data type. More information about data types can be found in Section 2.3.1.</div>
<p class="tdh_026">2.2.3.2     Entity Core Dimension</p>  

<div class="tdh_066">The entity core dimension defines the entity for which the fact is being reported. The entity should be reported using a common identifier that is unique to the entity and unchanging. For example, a Legal Entity Identifier (LEI), IRS number, or CUSIP number are static identifiers that can be linked to a specific entity in a financial report. Likewise, a social security number uniquely identifies a person working in the United States and does not change with time. Developers should avoid using identifiers that change or are ambiguous. Also, since reports may be public, using identifiers that contain private information, such as social security numbers, may not be advisable.</div>
<p class="tdh_026">2.2.3.3     Period Core Dimension</p>  

<div class="tdh_066">A period core dimension defines the period of time relevant to the fact. The period can be one of two types: an <i>instant</i> or a <i>duration</i>. Consider again the expense report example. Total expenses for the month are considered a duration because the data is measured from the start of the month to the end of the month. An instant period represents a measurement that occurs at a specific point in time. For example, the money in a bank account on any given day is an instant measure, the money available at that moment.</div>
<div class="tdh_066">The periodicity of the data should be of a resolution that makes sense for the data itself. Again, for an expense report, a monthly period dimension is logical. Long-term growth of a market fund, however, might dictate using a period dimension to represent a year or even longer. Conversely, rainfall totals could be represented in days. Instant period core dimensions are expressed using a single date. Duration period dimensions are expressed using a starting date and an ending date which marks the beginning and end of the period respectively.</div>
<div class="tdh_066">Like the concept core dimension, the period core dimension is required for all facts. If the data point describes information that does not change with time, such as genetic data, birth dates or a constant such as pi, a period can be defined as &#8220;forever.&#8221; The period core dimension must agree with the properties of the concept core dimension. If the concept&#8217;s period type property is defined as &#8220;instant,&#8221; only an instant period core dimension can intersect with facts that have that concept. Likewise, if the concept&#8217;s period type is &#8220;duration,&#8221; only a duration period core dimension can intersect with those facts. For more information on concept properties, see Section 2.2.6.2.</div>
<p class="tdh_026">2.2.3.4     Unit Core Dimension</p>  

<div class="tdh_066">The unit core dimension indicates the unit of measurement of a fact. A unit of measurement is a magnitude of a quantity, defined and adopted by convention or by law. An example unit would be &#8220;USD&#8221;</div>
<p><!-- Field: Page; Sequence: 22 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->17<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">(United States Dollars) for monetary values or &#8220;meters&#8221; for length. The units are expressed as a list of numerator units with an optional list of denominator units. This allows for compound units, such as dollars/share or miles/hour. It also allows for units such as meters<sup>2</sup> by specifying multiple &#8220;meter&#8221; units in the numerator.</div>
<div class="tdh_066">The unit core dimension is dictated by the data type property of the concept core dimension. For example, kilowatts/hour or megawatts/hour would be an appropriate unit for facts with a concept named EnergyProduced, which expresses the amount of total electricity created by a power plant. The unit core dimension is only applicable to concept core dimensions that have numeric data types.</div>
<div class="tdh_066">XBRL gives the flexibility to express facts in differing units on the same plane as an intersecting concept and unit dimension. The unit adds meaning to a numeric value. For example, &#8220;3&#8221; is a scalar value with no intrinsic meaning. When associated with a concept, the value can be known to be monetary. However, the specific type of monetary unit is still unclear. Adding a unit &#8220;USD&#8221; would indicate US dollars while &#8220;CAD&#8221; would be Canadian dollars. More than one unit can be expressed, allowing for both USD and CAD values for the same data point with an added unit differentiation.</div>
<div class="tdh_066">A set of standard units are defined in the <i>Units Registry</i>. The Units Registry has hundreds of defined units to qualify data ranging from currency to measurements such as meters, volts, and hectares (see <a href="https://specifications.xbrl.org/work-product-index-registries-units-registry-1.0.html"><span class="tdh_035"><i><u>XBRL Units Registry</u></i></span></a>).</div>
<div class="tdh_066">When expressing a numeric fact, it must contain a unit reference (see <i>XBRL 2.1, §4.6.2 The @unitRef attribute</i>).</div>
<p class="tdh_026">2.2.3.5     Language Core Dimension</p>  

<div class="tdh_066">The language core dimension specifies the language in which a non-numeric fact is reported. Language values must be represented with a valid BCP 47 language code (for more information, see <a href="https://tools.ietf.org/html/bcp47"><span class="tdh_035"><i><u>IETF BCP 47</u></i></span></a>). Language core dimensions should only be present on concept core dimensions that allow textual information and are optional in this case.</div>
<div class="tdh_066">If data is expected to be used in a multi-language environment, it is highly recommended that the language core dimension be employed. This involves using the &#8220;en-US&#8221; value for the language core dimension. Note that for reports that will be consumed in a primarily English-speaking environment (or an environment where only language is expected), the language core dimension can generally be omitted.</div>
<p class="tdh_026">2.2.3.6     Note Core ID Dimension</p>  

<div class="tdh_066">The note core ID dimension links a footnote or set of footnotes to one or more facts. More information about the note core ID dimension and XBRL footnotes is described in Section 2.2.9.</div>
<p class="tdh_026">2.2.3.7     Taxonomy-defined Dimensions</p>  

<div class="tdh_066">A taxonomy-defined dimension is a concept that exists for the purpose of grouping facts that should be interpreted in a similar way. Taxonomy-defined dimensions will be explored in greater detail in later sections. For now, consider taxonomy-defined dimensions to be concepts that do not directly define a fact but rather intersect with a fact to add further contextual or semantic information beyond what is added by the core dimensions already discussed.</div>
<p class="tdh_020"><a name="a_Ref8723734"></a><span class="tdh_024">2.2.4     </span>XBRL Dimension Details</p>  

<div class="tdh_066">Thus far certain XBRL dimensions, such as the concept core dimension, have been introduced. All the core dimensions of a concept in a taxonomy can be used in XBRL instance documents to define contextual information about data points. However, the core dimensions alone in most cases are not adequate to represent everything about the data. For example, if it is necessary to group data by regions or product types, additional data constructs will be required. For that, further <i>taxonomy-defined dimensions</i>, which are a special type of concept, must be added to create additional data dimensionality.</div>
<div class="tdh_066">Looking back at the expense example, dimensions must be defined for each fact to be represented in XBRL. For now, a simplistic approach that makes use of the concepts previously discussed can be</div>
<p><!-- Field: Page; Sequence: 23 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->18<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">beneficial in understanding how to define and use XBRL dimensions. Because of the nature of the data in the expense report, some of the XBRL dimensions will be the same for all facts.</div>
<div class="tdh_066"><a name="c2_core_dimension"></a>The core dimensions as relevant to the expense example used are listed in Table 2-1:</div>
<table class="tdh_077" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_204">
<td class="tdh_247"><span class="tdh_042"><b>Core Dimension</b></span></td>
<td class="tdh_259"><span class="tdh_042"><b>Description</b></span></td>
<td class="tdh_244"><span class="tdh_042"><b>Expense Example</b></span></td>
</tr>
<tr class="tdh_205">
<td class="tdh_184">Entity</td>
<td class="tdh_184">The entity reporting this value (the entity core dimension). Normally this is some sort of unique value, such as a LEI or tax number.</td>
<td class="tdh_184">Bob&#8217;s Household</td>
</tr>
<tr class="tdh_204">
<td class="tdh_184">Unit</td>
<td class="tdh_183">
<p class="tdh_076">The unit for a numeric value (the unit core dimension). The unit employed must be part of the <a href="https://specifications.xbrl.org/work-product-index-registries-units-registry-1.0.html"><span class="tdh_035"><i><u>XBRL Units Registry</u></i></span></a> (UTR) or otherwise defined. For non-numeric facts, such as a narrative description, the unit core dimension is not used.</p>  

<p class="tdh_076">Depending on the application, a numeric value can be represented by multiple facts each with a specific unit. Alternatively, an entity may disclose data in another currency or measurement.</p>  

</td>
<td class="tdh_183">
<p class="tdh_076">(not shown)</p>  

<p class="tdh_076">USD</p>  

</td>
</tr>
<tr class="tdh_205">
<td class="tdh_184">Period</td>
<td class="tdh_184">Defines the time domain for the fact (the period core dimension). This time domain represents the period of time to which a fact is applicable. These are represented in ISO-8601 format.</td>
<td class="tdh_183">
<p class="tdh_076">January</p>  

<p class="tdh_076">2019-01-31</p>  

</td>
</tr>
<tr class="tdh_204">
<td class="tdh_184">Language</td>
<td class="tdh_184">The language in which a fact is reported (the language core dimension). This dimension can be defined for non-numeric facts. Like units, the narrative could be represented in multiple facts using different languages. Language types are represented using the <a href="https://tools.ietf.org/html/bcp47"><span class="tdh_035"><i><u>BCP 47 Codes</u></i></span></a>.</td>
<td class="tdh_184">[n/a]</td>
</tr>
</tbody>
</table>
<p class="tdh_106"><a name="a_Ref6406131"></a><a name="a_Ref6406151"></a>Table 2-1. XBRL dimensions and their relation to the expense example (Figure 2-6)</p>  

<div class="tdh_066">The nature of the data dictates how these XBRL dimensions apply. For instance, in the previous example, expenses are always monetary values measured in United States Dollars, which suggests using a unit core dimension of &#8220;USD.&#8221; The entity in the example is &#8220;Bob&#8217;s Household&#8221; (which is not an ideal identifier but is sufficient for a simple example). The language core dimension does not apply in this case because the data contains no textual facts. Otherwise, these dimensions are applicable for all the data in the expenses table.</div>
<div class="tdh_066">The period core dimension, however, changes column to column. For the first column, the period dimension represents the month of January. The next dimension represents February and so on. With all these dimensions defined, the concepts and the core dimensions, every cell of data in the table can be represented as an XBRL fact.</div>
<div class="tdh_066">There are multiple ways to organize data and relationships. In addition, there are cases where it is necessary to disaggregate similar data. For example, Bob may want to break his expenses down by his dependents. The above core dimensions will remain the same but now the fact can be qualified or dimensionalized further by additional data relationships. This is explored in Section 2.2.8. For now, the XBRL core dimensions will be explored as a means to add specified semantic meaning to data.</div>
<p><!-- Field: Page; Sequence: 24 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->19<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_020"><a name="a_Ref8644940"></a><span class="tdh_024">2.2.5     </span>Concepts</p>  

<div class="tdh_066"><a name="c2_concept"></a>A <i>concept</i> is a semantic identifier as defined by the taxonomy. It is the basic building block of a taxonomy, and all the data dimensions within that taxonomy refer to relationships between or among concepts. The term concept core dimensions refers only to those concepts that define the semantic idea a data value is meant to represent.</div>
<div class="tdh_066">Other types of concepts may be used as organizational containers for concept core dimensions that are semantically related. These are called <i>grouping concepts</i>, and they define structures within a taxonomy, such as an XBRL <i>table</i> structure or a <i>domain</i> of possible values. Still other concepts may be organized along a taxonomy-defined dimension to specify axes along which facts vary. Because concepts are the basic unit of semantic and structural information in XBRL, concepts will have a relational position with respect to other concepts within the taxonomy. Combining concept core dimensions with grouping concepts and the concepts that make up taxonomy-defined dimensions can be used to create complex structures with self-describing semantic meaning. For example, a fact may have a concept core dimension of SalesRevenue, and this could intersect with the taxonomy-defined dimension Region, which may have further differentiating concept members such as EasternRegion and WesternRegion. This may all be contained by a concept defining a table of SalesByRegion.</div>
<p class="tdh_099"><img class="tdh_143" src="http://files.xbrl.us/images/tdh/tdh_p1_012.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref24370238"></a>Figure 2-10. Types of concepts.</p>  

<div class="tdh_066">As illustrated in Figure 2-10, concept core dimensions define a fact value. Grouping concepts are used to group concepts that are semantically related. Taxonomy-defined dimensions organize concepts to define additional dimensionality. Taxonomy-defined dimensions may or may not have member concepts. Again, more information on taxonomy-defined dimensions and how they add dimensionality to XBRL facts is discussed in Sections 2.2.8 and Chapter 3.</div>
<div class="tdh_066">Concepts have properties that define their usage and the types of data they can describe, which is discussed in greater detail in the next section. The properties of a concept also dictate the types of other XBRL dimensions that can intersect with the data.</div>
<p class="tdh_020"><a name="a_Ref8644940"></a><span class="tdh_024">2.2.6     </span>Concept Details</p>  

<p class="tdh_026">2.2.6.1     Overview</p>  

<div class="tdh_066">Concepts are the intrinsic building blocks of XBRL. These semantic identifiers define facts at the most basic level. How is the semantic meaning behind these numeric data points implemented in XBRL?</div>
<div class="tdh_066">A deeper examination of the expense example yields some answers. Consider again Figure 2-4, where categories of expenses are rows (line items) and columns represent the months in which those expenses occurred. Because this example is so simple, the table line items (Column A) naturally lend themselves to</div>
<p><!-- Field: Page; Sequence: 25 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->20<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">becoming the concept core dimension. Each of these concepts, such as FoodExpenses, EntertainmentExpenses, etc., is linked to a numeric value in Columns B-E, producing the beginnings of an XBRL fact. Defining concepts not only defines the discrete, semantic identifiers in the taxonomy, it also allows the properties of the concepts to add further qualitative information to the data points.</div>
<p class="tdh_026"><a name="c2_concept_property"></a><a name="a_Ref6488253"></a>2.2.6.2     Concept Properties</p>  

<div class="tdh_066">In addition to defining the semantic information associated with a fact, concepts themselves have <i>properties</i>. These properties can be thought of as ways to characterize the type of data to which the concept can be linked. This can include the type of data (numeric, textual), whether the data can be nil or undefined, or whether the concept itself can be associated with data at all.</div>
<div class="tdh_066">In the example presented above, these concepts are all expenses, so they can have the same properties. Again, this is a simplistic approach; for real data, the properties of the concepts should vary with the information they are meant to represent. For now, a simplistic view can help to illustrate the basic types of properties concepts can possess and how they map onto a real-world data set. Table 2-2 defines the possible properties of a concept and how they are represented in the expense example.</div>
<table class="tdh_077" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_202">
<td class="tdh_002"><span class="tdh_042"><b>Properties</b></span></td>
<td class="tdh_002"><span class="tdh_042"><b>Description</b></span></td>
<td class="tdh_002"><span class="tdh_042"><b>Expense Example</b></span></td>
</tr>
<tr class="tdh_205">
<td class="tdh_184">Name</td>
<td class="tdh_184">Name of the concept.</td>
<td class="tdh_185">FoodExpense, RentExpense, etc.</td>
</tr>
<tr class="tdh_204">
<td class="tdh_184">Period Type</td>
<td class="tdh_184">The basic intersecting period core dimension that can be <i>instant</i> or <i>duration</i>. Period dimensions are discussed in Section 2.2.4.3.</td>
<td class="tdh_184">Duration</td>
</tr>
<tr class="tdh_205">
<td class="tdh_184">Balance Type</td>
<td class="tdh_184">An optional qualifying property that can be <i>debit</i> or <i>credit</i>.</td>
<td class="tdh_184">Debit</td>
</tr>
<tr class="tdh_204">
<td class="tdh_184">Nillable</td>
<td class="tdh_184">An optional property indicating an intersecting fact can be nil or reported with no value regardless of its data type. Note that this is not the same as having a value of 0.</td>
<td class="tdh_184">Not nillable</td>
</tr>
<tr class="tdh_205">
<td class="tdh_184">Abstract</td>
<td class="tdh_184">A property indicating the concept is specifically intended for organizational purposes within the taxonomy.</td>
<td class="tdh_184">False</td>
</tr>
<tr class="tdh_204">
<td class="tdh_184">Data Type</td>
<td class="tdh_184">The type of data the concept can represent. Data types are formally defined and discussed in Section 2.3.1.</td>
<td class="tdh_184">Monetary</td>
</tr>
<tr class="tdh_205">
<td class="tdh_184">Substitution Group</td>
<td class="tdh_184">A property categorizing the concept as one of a number of types, such as item, dimension, or enumeration, among others.</td>
<td class="tdh_184">Item</td>
</tr>
</tbody>
</table>
<p class="tdh_106"> <a name="a_Ref6407927"></a>Table 2-2. Concept properties and their relation to the expense example (Figure 2-6)</p>  

<div class="tdh_066">The nature of our data dictates these property choices. For example, the expenses are always monetary values expressed for a month. Also, because these expenses always have a value, they are not nillable.</div>
<div class="tdh_066">The values of these properties for each concept are stored in the taxonomy itself. The <i>taxonomy schema</i> is defined using the <a href="https://specifications.xbrl.org/work-product-index-group-base-spec-base-spec.html"><span class="tdh_035"><i><u>XBRL Specification</u></i></span></a> and is in XML format. Example 2-1 is an excerpt from an XBRL taxonomy schema showing the definition of one of the example concepts:</div>
<p><!-- Field: Page; Sequence: 26 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->21<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_106"><img class="tdh_115" src="http://files.xbrl.us/images/tdh/tdh_p1_example_21.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref6408233"></a>Example 2-1. An example XBRL concept definition</p>  

<div class="tdh_066">The element tag describes the XBRL concept using XML syntax. The XML syntax is the same syntax as XML schema documents. For more information on XML Schema, see Appendix A. The attributes of the XML element represent the properties of the concept as described above. Attributes with the &#8220;xbrli&#8221; namespace are defined in the XBRL Instance Schema. For more information on the XBRL Instance Schema, see Appendix A.</div>
<p class="tdh_026">2.2.6.3     Concept Naming</p>  

<div class="tdh_066">As one might imagine, a taxonomy with many concepts demands good organization and consistent concept names. The <a href="https://xbrl.us/xbrl-reference/style-guide/"><span class="tdh_035"><i><u>XBRL US Style Guide</u></i></span></a> defines naming methods and constraints to avoid problems in building and maintaining a taxonomy. To be in agreement with that document and reflect consistency, concept names in this handbook will use upper <i>camel case</i> naming (FoodExpense rather than foodExpense).</div>
<div class="tdh_066">For example, how should a concept used for facts expressing maximum electrical component heat dissipation be named? The following are all possibilities:</div>
<p class="tdh_062">ElectricalComponentHeatDissipation</p>  

<p class="tdh_062">ComponentHeatDissipation</p>  

<p class="tdh_062">MaximumElectricalComponentHeatDissipation</p>  

<p class="tdh_062">MaximumElectricalComponentHeatDissipationInWatts</p>  

<p class="tdh_068">TotalMaximumElectricalComponentHeatDissipationInWatts</p>  

<div class="tdh_066">There are a lot of options, but certain rules should be kept in mind when creating concept names. For example, adding &#8220;watts&#8221; to the name is considered bad practice because &#8220;watts&#8221; is a unit (which should be dictated by the unit core dimension). Prior to defining concept names, the <a href="https://xbrl.us/xbrl-reference/style-guide/"><span class="tdh_035"><i><u>XBRL US Style Guide</u></i></span></a> should be reviewed.</div>
<p class="tdh_026"><a name="a_Ref11751469"></a>2.2.6.4     Concept Labels</p>  

<div class="tdh_066">XBRL defines an adjunct to concepts called labels or label roles. Given a specific usage, labels and label roles provide further information and documentation associated with a concept. For example, the default label role for the concept described in the previous section might be &#8220;Maximum continuous heat dissipation in a normal operating environment,&#8221; while the documentation label role might specify more information, such as the authoritative source.</div>
<div class="tdh_066">Label roles can also be used to aid preparers in understanding how a concept should be used or not used. For example, if a total role is not defined, preparers can assume that the concept should not be used as a total.</div>
<p class="tdh_020"><span class="tdh_024">2.2.7     </span>Fact Properties</p>  

<div class="tdh_066">Facts inherit properties from their concept core dimension. These include the data type, the balance type, and nillable. These properties are determined through the concept core dimension, rather than the fact itself. However, facts do possess properties regarding precision and scaling that are specific to the fact itself. For instance, the concept EmployeeTurnoverRate might have a data type requiring a decimal</div>
<p><!-- Field: Page; Sequence: 27 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->22<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">number, and this would apply to every fact that is associated with this concept. However, a fact with this concept can have a <i>decimals</i> property specified that would indicate the precision of that particular fact and only that fact.</div>
<div class="tdh_066">The names and types of properties that can be specified on a fact by fact basis change, depending on the transport model. Consult the specification for the specific transport format for more information.</div>
<p class="tdh_020"><a name="a_Ref8723381"></a><span class="tdh_024">2.2.8     </span>Adding Taxonomy-defined Dimensions</p>  

<div class="tdh_066"><a name="c2_taxonomy_defined_dimension"></a>As stated above, there are many XBRL dimensions to organize facts. Thus far, dimensions that are defined by the <a href="https://specifications.xbrl.org/work-product-index-group-base-spec-base-spec.html"><span class="tdh_035"><i><u>XBRL Specification</u></i></span></a> have been the focus of this chapter. These core dimensions, such as the concept core dimension and period core dimension, can provide useful additional meaning and structure to data. However, often there will be a need to organize facts by a custom structure. There are also times when a simple data model with one or two data dimensions cannot accurately represent the complexity of the relationships among the data points. In these cases, adding further dimensionality is a key step to building an XBRL data model. For example, a retail chain might want to report its profits by both region and time, or an agricultural industry could need to indicate crop growth by both crop type and the types of fertilizers used. In XBRL, this can be accomplished by adding layers of custom dimensionality through taxonomy-defined dimensions.</div>
<div class="tdh_066">A taxonomy-defined dimension is a grouping of concepts that is used to add organizational structure to facts. These dimensional concepts should not be directly associated with a data point but rather are employed to indicate additional contextual information beyond the simple semantic identifier or what is provided through any of the other core dimensions. Expanding the expense example by attributing the monthly expenses to two people in the same household creates a level of complexity that cannot be easily represented with only concepts. Previously, there were only two dimensions: expenses (as rows) and months (as columns). If the data set tracked the expenses of Bob&#8217;s children, Jared and Allyson, more columns would be added as follows:</div>
<p class="tdh_099"><img class="tdh_120" src="http://files.xbrl.us/images/tdh/tdh_p1_013.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref6409682"></a>Figure 2-11. Multiple facts and dimensions in an expense example</p>  

<div class="tdh_066">Within Figure 2-11, two &#8220;person&#8221; dimensions are expressed in the data itself, Jared and Allyson, for each month, making a total of three dimensions for the resulting data model: concepts (line items or rows), periods (columns), and person (subcolumns). How can the XBRL taxonomy be adapted to show this added layer of dimensionality? One could add additional concepts as part of the concept core dimension, such as FoodExpensesForJared and FoodExpensesForAllyson, but this could quickly become cumbersome and tedious once the data set becomes sufficiently large and complex.</div>
<div class="tdh_066">A taxonomy-defined dimension provides an answer to this situation by disaggregating Bob&#8217;s Household Expenses. This new XBRL dimension is defined by a concept that represents the nature of an <i>axis</i> in the data set. In the example, a concept named Person would be added to the taxonomy. Good practice would also dictate that a suffix is appended to the name of this concept to indicate that this is a taxonomy-defined dimension and should not itself be used as a concept core dimension. In other words, this new concept should not be used directly with any one fact. For more information on suffixes, see the <a href="https://xbrl.us/xbrl-reference/style-guide/"><span class="tdh_035"><i><u>XBRL Style Guide</u></i></span></a>. This would make the final concept name PersonAxis.</div>
<p><!-- Field: Page; Sequence: 28 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->23<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Now that there is a concept to describe the taxonomy-defined dimension, the components, or members, of this dimension must be described. In the example, this would be Jared and Allyson, the two people who belong to the reporting entity, &#8220;Bob&#8217;s Household.&#8221; They therefore belong to the new PersonAxis. XBRL offers numerous ways to express these components, but for this example, concepts named Jared and Allyson will be used. Again, good style practice and clarity suggest adding a suffix to these concept names to indicate they should not be used as concept core dimensions. Thus, they will be named JaredMember and AllysonMember. For a more in-depth discussion on the other options to express the components of a taxonomy-defined dimension, see Section 3.4.2.</div>
<div class="tdh_066">When preparing XBRL in XML or Inline XBRL, preparers can provide single references that define the entity core dimension, period core dimension, and if available, taxonomy-defined dimensions. This grouping of references, which are called <i>contexts</i>, allow the preparer to create a single grouping once and apply it to multiple facts. For example, in the expenses example, a context could be created to represent the period January plus the entity Bob&#8217;s Household plus the Jared component of the taxonomy-defined dimension Person. This context, which is shown in Example 2-2, has been given the name JanuaryForJared. It can be used to identify multiple facts on the expense table. The advantage of using contexts is that the combination of period/entity/taxonomy-defined dimension(s) need only be created once and can be used multiple times for different facts.</div>
<div class="tdh_066">With the context defined, the XBRL example can be updated to use it. Remember, for XBRL in XML and Inline XBRL, these dimensions are added to the XBRL context element, so first examine the updated context definition:</div>
<p class="tdh_105"><img class="tdh_153" src="http://files.xbrl.us/images/tdh/tdh_p1_example_22.jpg" alt="" /></p>  

<p class="tdh_104"><a name="a_Ref8732307"></a>Example 2-2. An XBRL fact with a taxonomy-defined dimension in XML</p>  

<div class="tdh_066">Now there is <i>segment</i> for the context. A segment is a way of adding taxonomy-defined dimensions. This segment uses the dimension example:PersonAxis and the component for that dimension example:JaredMember. The identifier for the context also changed to reflect this XBRL dimension. Note that context identifiers are used to link facts to contexts and have no meaning on their own. The fact now uses this identifier for the context. Segments are discussed in more detail in Section 3.5.5.</div>
<div class="tdh_066">Figure 2-12 illustrates how the context JanuaryForJared would be used in the expenses example. This context can be used for all ten reported facts as shown below. Different concept core dimensions (for food expenses, fuel expenses, etc.) would intersect with the JanuaryForJared context to represent separate facts.</div>
<p><!-- Field: Page; Sequence: 29 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->24<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_099"><span class="tdh_041"><img class="tdh_147" src="http://files.xbrl.us/images/tdh/tdh_p1_014.jpg" alt="A close up of a map Description automatically generated" /></span></p>  

<p class="tdh_106"><a name="a_Ref8733091"></a>Figure 2-12. Expense example with an illustrated XBRL in XML context</p>  

<div class="tdh_066">Inline XBRL (Example 2-3) uses the same context definitions as XBRL in XML.</div>
<p class="tdh_105"><img class="tdh_122" src="http://files.xbrl.us/images/tdh/tdh_p1_example_23.jpg" alt="" /></p>  

<p class="tdh_104"><a name="a_Ref23240693"></a>Example 2-3. An XBRL fact with a taxonomy-defined dimension in Inline XBRL</p>  

<div class="tdh_066">JSON and CSV do not support the use of contexts. These approaches handle adding taxonomy-defined dimensions differently. The JSON syntax for this change appears in Example 2-4.</div>
<p class="tdh_105"><img class="tdh_121" src="http://files.xbrl.us/images/tdh/tdh_p1_example_24.jpg" alt="" /></p>  

<p class="tdh_104"><a name="a_Ref23240728"></a>Example 2-4. An XBRL fact with a taxonomy-defined dimension in JSON</p>  

<div class="tdh_066">In JSON, the additional XBRL dimension has been added to the fact, which uses the taxonomy-defined dimension as the key and the member concept as the value. Additional taxonomy-defined dimensions can be included this way.</div>
<p><!-- Field: Page; Sequence: 30 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->25<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Taxonomy-defined dimensions allow for even greater flexibility in data as any number of additional axes can be added to the data model. In this example, they were used to disaggregate composite data into additional data dimensions, but taxonomy-defined dimensions can be used to represent many other types of data architecture scenarios. How to design XBRL dimensions for example data models is discussed in Chapter 3.</div>
<p class="tdh_020"><a name="a_Ref24463084"></a><span class="tdh_024">2.2.9     </span>Attaching Footnotes to Facts</p>  

<div class="tdh_066">Traditionally a footnote adds further explanatory information to a statement or fact. In XBRL, footnotes are created through relationships between note text and facts using the footnote arc. One instance of footnote text can be linked to multiple facts. The <i>note core ID dimension</i> is the dimension on the fact that associates the fact with one or more footnotes arcs. Note that because more than one fact can reference the same footnote, the note ID core dimension does not confer any uniqueness to the fact.</div>
<div class="tdh_027"><a name="a_Toc24107532"></a><a name="a_Toc23337678"></a>2.3   Machine-readability</div>
<div class="tdh_066">With a better understanding of what an XBRL fact entails, it becomes clear that the fact is the basic unit of the XBRL transport model. With its XBRL dimensions, the fact uniquely represents data points within the semantic data model and becomes self-describing. Data consumers can interpret the fact as necessary with the information provided through the XBRL dimension, the relations to other facts, and the content of the fact itself.</div>
<div class="tdh_066">A key facet of this interpretation, though, and one of the strengths and purposes of XBRL as a data model, is maintaining machine-readability. While XBRL offers the means to connect human-readable formats with machine-readability, its purpose is allowing a consuming system to take its facts and realign them appropriately to consumer data models and reporting structures. The system that receives the XBRL report should be able to interpret the transport model and all its facts correctly. Therefore, it is the job of the XBRL taxonomy developer to ensure XBRL facts are consistent and appear in a predictable, anticipated manner.</div>
<div class="tdh_066">XBRL describes a format for data storage, organization, and transport. Most XBRL software can provide additional functionality, such as validation and mathematical comparisons. Because XBRL describes its own data model, software can perform these additional tasks with little or no additional development.</div>
<p class="tdh_020"><a name="a_Ref17795009"></a><span class="tdh_024">2.3.1     </span>Data Types</p>  

<div class="tdh_066">A key facet of maintaining a consistent, predictable structure pertaining to an XBRL fact is clearly defining the fact&#8217;s data type. Data types have been briefly discussed, but this section aims to take a deeper dive to explain how XBRL enables machine-readability. For a consumer system to be able to translate incoming XBRL facts appropriately, those facts must conform to that system&#8217;s expectations concerning data types. The data type selection is also critical to aid in self-validation and documentation of the fact content as intersected by the concept. For example, if a data type specifies that a fact&#8217;s value must be positive and non-zero, then it becomes a simple matter for XBRL software to indicate an erroneous entry or report a fact error.</div>
<div class="tdh_066">At a basic level, a <i>data type</i> defines the set of possible values for a fact. Data types can be simple, such as an integer, or they can have additional constraints, such as a non-negative integer. Data types can be generally grouped as <i>numeric</i> or <i>non-numeric</i>. Numeric data types can be used in mathematical operations. They cannot contain text. Non-numeric data types are not meant to be used mathematically. For example, a data point expressing a tax identification number may be expressed only in digits. However, the data type for that fact should not be numeric as there is no logical reason to perform mathematical operations on this identifier.</div>
<div class="tdh_066">As previously stated, a fact&#8217;s data type is determined by the data type property of its concept core dimension. Accordingly, the concept&#8217;s data type should be dictated by the nature of the data it is meant to represent. A concept representing total energy output of a power plant, for example, suggests a data type that allows decimal precision. Similarly, a concept describing the number of people answering a survey should dictate an integer data type.</div>
<p><!-- Field: Page; Sequence: 31 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->26<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">XBRL derives its data types from the standard XML data types. Table 2-3 contains a sampling of common XBRL data types.</div>
<table class="tdh_077" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_202">
<td class="tdh_248"><span class="tdh_042"><b>Data Type</b></span></td>
<td class="tdh_261"><span class="tdh_042"><b>Description</b></span></td>
</tr>
<tr class="tdh_205">
<td class="tdh_186">stringItemType</td>
<td class="tdh_186">Represents character strings in XML.</td>
</tr>
<tr class="tdh_204">
<td class="tdh_186">booleanItemType</td>
<td class="tdh_186">Represents the values of two-valued logic (true, false).</td>
</tr>
<tr class="tdh_205">
<td class="tdh_186">decimalItemType</td>
<td class="tdh_186">Represents a subset of real numbers, which can be represented by decimal numerals.</td>
</tr>
<tr class="tdh_204">
<td class="tdh_186">dateTimeItemType</td>
<td class="tdh_186">Represents instants of time, optionally marked with a time zone offset.</td>
</tr>
<tr class="tdh_205">
<td class="tdh_186">integerItemType</td>
<td class="tdh_186">Represents the standard mathematical concept of integer numbers by fixing the fractional digits of <i>decimal </i>to be 0 and prohibiting the trailing decimal point.</td>
</tr>
<tr class="tdh_204">
<td class="tdh_186">monetaryItemType</td>
<td class="tdh_186">Represents a decimal with the added constraint of a currency unit.</td>
</tr>
<tr class="tdh_205">
<td class="tdh_186">qNameItemType</td>
<td class="tdh_186">Represents a qualified XML name.</td>
</tr>
</tbody>
</table>
<p class="tdh_106"><a name="a_Ref9339264"></a>Table 2-3. Common XBRL data types</p>  

<div class="tdh_066">Many standard taxonomies contain additional data types. Developers can also create their own data types. Data type extensibility is discussed in Section 3.6.1.1. Because data types are built into XML, any program that can understand XML will be able to validate them at a basic level, even custom data types that are properly extended from standard data types. See Appendix A for more information on XML data types.</div>
<p class="tdh_020"><span class="tdh_024">2.3.2     </span>Mathematical Consistency</p>  

<div class="tdh_066">Facts with a numeric data type must have a decimals or precision property that states how mathematically precise the value of the fact is. Because all numeric facts must have precision, XBRL software can maintain precision when performing mathematical calculations. Given this, when comparing a computed value versus a fact value, XBRL software can automatically accommodate for rounding errors.</div>
<p class="tdh_020"><span class="tdh_024">2.3.3     </span>Transformation and Interpretation</p>  

<div class="tdh_066">There are various formats to express values for data types such as numbers and dates. XBRL uses specific formats for these data types as governed by the XML specification. However, Inline XBRL offers additional instructions for XBRL software to convert human readable expressions of this information into the appropriate data type format. For example, an XBRL date must be in ISO 8601 format but many textual dates are written in descriptive language. An XBRL <i>transformation</i> describes how the descriptive language can be converted to the appropriate format. For a list of rules and more information, see the <a href="https://specifications.xbrl.org/work-product-index-inline-xbrl-transformation-registry-3.html"><span class="tdh_035"><i><u>XBRL Transformation Registry</u></i></span>.</a></div>
<div class="tdh_066">Inline XBRL also offers a <i>scaling</i> property on individual facts, to indicate to XBRL software that the value of the fact must be scaled before it is interpreted. For example, a table of facts may be expressed in millions without the trailing zeros to aid in human readability but Inline XBRL has appropriate scaling so the value of 123 is interpreted as 123000000.</div>
<div class="tdh_027"><a name="a_Toc24107533"></a><a name="a_Toc23337679"></a>2.4   The Taxonomy</div>
<div class="tdh_066"><a name="c2_taxonomy_structure"></a>With a high-level understanding of basic XBRL constructs and how those constructs intersect to represent a fact, XBRL developers can now explore the structure and components of an XBRL taxonomy. As mentioned previously, XBRL taxonomies define a semantic data model used for transport between</div>
<p><!-- Field: Page; Sequence: 32 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->27<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">originating preparers and consumers, both of whom potentially have semantic data models of their own to store, analyze, and report data. An XBRL taxonomy may represent semantic relationships within either the originating model or the consumer model, and it may also define its own relationships depending on the use cases. Thus far, the discussion in this document has focused on how XBRL facts are represented in an XBRL report with their associated dimensions, but without the taxonomy and its roadmap of how the dimensions relate to each other, the XBRL report lacks semantic meaning.</div>
<div class="tdh_066">Though XBRL taxonomies may greatly differ concerning the nature of the data they are intended to represent, taxonomies all employ the same XBRL structures, tools, and rules to function as a transport model.</div>
<p class="tdh_020"><span class="tdh_024">2.4.1     </span>Taxonomy Characteristics</p>  

<div class="tdh_066">The basic purpose of a taxonomy is to organize concepts into a <i>hierarchy</i>. A hierarchy defines how concepts relate to one another. It is often visualized as a tree structure (Figure 2-13).</div>
<p class="tdh_099"><img class="tdh_159" src="http://files.xbrl.us/images/tdh/tdh_p1_015.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref9511710"></a>Figure 2-13. An example hierarchical taxonomy structure</p>  

<div class="tdh_066">There are three basic structures that can be visualized within a taxonomy: <i>calculations</i>, <i>presentations</i>, and <i>definitions</i>. All three are present within Figure 2-13. More on these topics is discussed later in this section and in Chapter 3. Taxonomies typically possess one or more <i>entry points</i>. An entry point is a collection of concept groups that have been joined for a specific use case. For example, an entry point may consist of all of the presentations, calculations, and definitions that are relevant to banking within a financial reporting taxonomy. Entry points help organize concept groups by use cases and can aid preparers in navigating a taxonomy and locating the sections that apply to their reporting needs.</div>
<div class="tdh_066">Note that every item in this structure is in fact a concept, though only the concepts that fall directly beneath a table in Figure 2-13 are concepts that can intersect with facts; these are concept core dimensions. Only the concepts in the entry point should be used to describe data that is expressed by that entry point, although other concepts may exist for other entry points. The other concepts are either member concepts or other structural containers, such as tables and axes, and must be abstract. This represents <i>concept grouping</i>, which is a way to define hierarchical relationships within the taxonomy. Concept groups can contain any number of other concepts and concept groups, just as a branch of a tree can connect to many smaller branches, some of which also lead to many other branches, and so on. This hierarchical structure and the concept names represent the transport data model.</div>
<p><!-- Field: Page; Sequence: 33 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->28<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">For an XBRL hierarchical model, each <i>node</i> (or element of the tree) is considered a concept. In this way a concept identifies a unique position within the taxonomy for a specific data item, an XBRL dimension, or a grouping of dimensions. The root concept or node is at the top of the tree and may represent an entry point or a presentation.</div>
<div class="tdh_066">For example, Figure 2-14 reflects a hierarchical structure for representing types of aircraft.</div>
<p class="tdh_099"><img class="tdh_113" src="http://files.xbrl.us/images/tdh/tdh_p1_016.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref9931405"></a>Figure 2-14. An example hierarchical representation of concepts that describes types of aircraft</p>  

<div class="tdh_066">The first column specifies the concept name. The second column represents the standard label for the concept. For example, CommonDomainMembersAbstract has a label that indicates it is an abstract. The label for the CommonTable concept indicates it is a table container. This may seem redundant, but it is important since each concept can have multiple labels associated with it for differing roles. More on how concept names and properties influence their roles is discussed in the next section.</div>
<div class="tdh_066">Children of the concept are indented in this case. This is a common way of expressing the <i>parent/child</i> relationship. A concept&#8217;s parent is a node one step higher in the hierarchy. A concept&#8217;s <i>siblings</i> share the same parent concept. It should be noted that while XBRL uses a hierarchical structure to organize concepts, the parent/child relationship within XBRL does not imply or allow the inheritance of properties. For example, while the concepts shown in Figure 2-13 and Figure 2-14 are children of the table and axis concepts, they do not inherit the properties of those parent table or axis concepts. It should also be noted that, while concepts can have differing roles and exist within multiple different presentations, specific relationships defined between concepts exist within at least <i>one </i>of these types of relationship structures. Concept A cannot be a parent of Concept B if Concepts A and B are not within the same hierarchical structure in some entry point of the taxonomy. More on parent/child relationships and inheritance is discussed in Section 3.4.3.</div>
<div class="tdh_066">A taxonomy does not have to be a single, self-contained organization. Taxonomies can reference and contain other taxonomies. The external taxonomies referenced in this way are known as a <i>Discoverable Taxonomy Set</i> (DTS) for the prime taxonomy. The external taxonomies can themselves reference additional taxonomies. All of the taxonomies in this chain are required to understand the prime taxonomy. Employing a DTS is very useful as it allows developers to build on existing standards for specific applications.</div>
<p class="tdh_020"><a name="a_Ref14164440"></a><span class="tdh_024">2.4.2     </span>Concept Properties and How They Relate Concepts to Each Other</p>  

<div class="tdh_066">The organization, selection, and naming of concepts are critical to creating a well-formed taxonomy that matches the real-world data application. Each concept has properties associated with it, as previously discussed. In terms of taxonomy structure and organization, the concept name, the abstract property, and the substitution group property can express the concept&#8217;s use within the taxonomy. Often all three should be addressed appropriately to indicate a concept&#8217;s role.</div>
<div class="tdh_066">The first of these properties is the concept name, which, as discussed before, is a machine-readable name created to describe the concept in a consistent manner. Naming conventions should be employed following certain style rules (check the <a href="https://xbrl.us/xbrl-reference/style-guide/"><span class="tdh_035"><i><u>XBRL US Style Guide</u></i></span></a> for language and reference styles). Of note in this case is the use of specific suffixes to indicate a concept&#8217;s role. Suffixes should be appended to certain concept names to help users distinguish between their uses (for example, &#8220;Abstract&#8221; for an abstract concept, &#8220;Member&#8221; for a concept that is an axis member, or &#8220;Axis&#8221; for the concept container for</div>
<p><!-- Field: Page; Sequence: 34 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->29<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">an axis). These suffixes were briefly introduced in Section 2.2.8, where example concepts belonging to taxonomy-defined dimensions were defined in XBRL.</div>
<div class="tdh_066">The second property is the abstract property. Concepts that do not actually intersect facts often have their abstract property set to &#8220;true.&#8221; This specifically indicates that a concept is not a concept core dimension but rather an organizational item. Grouping concepts have the abstract property set to &#8220;true.&#8221;</div>
<div class="tdh_066">Finally, there is the substitution group property. The substitution group property can aid in defining a concept&#8217;s role more specifically by grouping it with other like concepts. Concepts with the same substitution group have similar uses. Example substitution groups include dimension, item, or hypercube.</div>
<div class="tdh_066">These ideas will be discussed in greater detail in Chapters 3 and 5. Concept properties are vital in defining the concept&#8217;s role in the taxonomy and how each concept relates to other concepts within the taxonomy.</div>
<p class="tdh_020"><span class="tdh_024">2.4.3     </span>Components of a Taxonomy</p>  

<div class="tdh_066">A taxonomy is comprised of two main components: schema documents and one or more linkbases. The combination of the linkbase and the schema is what makes the taxonomy self-describing. Each of the components of a taxonomy is described in the following sections. All XBRL taxonomies must be defined in XML using XML constructs, regardless of whether or not the data to be reported is actually transported in XML.</div>
<p class="tdh_026">2.4.3.1     Schema</p>  

<div class="tdh_066">A <i>schema</i> refers to a description of an XML document. Schema typically express constraints on the structure and content of an XML document, above the simple syntactical constraints of the XML language itself. To use an analogy, XML can be thought of as an alphabet for a written language. The XML schema is like a dictionary that contains all the allowable words, their definitions, and their grammatical uses. With these components combined, the language can be used to write a story. With an XML schema, the constructs of the taxonomy and their usage can be defined.</div>
<div class="tdh_066">XBRL also requires the use of the XSD (XML Schema Definition) format in describing the elements of the schema. Schemas typically include information such as element (concept) declarations, attribute declarations, and property definitions for concepts. They can also include custom data types. More information on developing the schema portion of a taxonomy is available in Chapter 5.</div>
<p class="tdh_026">2.4.3.2     Linkbases</p>  

<div class="tdh_066"><a name="c2_linkbase"></a>If the XML schema is the dictionary of the taxonomy, the <i>linkbase</i> is an outline of the story and a primer on how to organize its many chapters. A linkbase shows how the concepts of the taxonomy relate to each other. Linkbases accomplish this through declaring <i>arcs</i> (which can be thought of as relationships) between concepts or between concepts and other resources, some of which may be external to the taxonomy itself.</div>
<div class="tdh_066">Like the schema document, linkbases must be defined with, and adhere, to XML constructs and standards. There are multiple types of linkbases. One or more of each type can exist in a taxonomy. If the taxonomy allows extensibility, preparers may be able to define custom versions of one or more of these types of linkbases.</div>
<p class="tdh_032">2.4.3.2.1     Presentation Relationships</p>  

<div class="tdh_066">The presentation linkbase defines one or more hierarchical structures of the concepts. This allows the taxonomy to be properly organized, and it permits XBRL rendering software to create visual representations of the taxonomy that are human-readable and easily navigable. Preparers using the taxonomy can view the hierarchy of concepts, which provides additional meaning beyond the XBRL dimensions (Figure 2-15).</div>
<p><!-- Field: Page; Sequence: 35 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->30<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_099"><img class="tdh_137" src="http://files.xbrl.us/images/tdh/tdh_p1_017.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref9946203"></a>Figure 2-15. A presentation within a sample taxonomy visualized through XBRL software</p>  

<div class="tdh_066">Concept labels (discussed in Section 2.2.6.4) are particularly important within a presentation. Labels instruct the rendering software (such as Arelle) on how to display the presentation and which labels to associate with the concepts in the presentation hierarchy. They may also dictate how the concept is interpreted within a specific presentation. Concepts may have multiple different labels defined (such as presentation labels, terse labels, and verbose labels), each designed for different display or interpretation purposes. For example, presentation line items can carry certain characteristics, such as whether a numeric fact should be displayed in its negated form. Reporting data for &#8220;Income (Loss)&#8221; may be a situation where a negative fact represents that loss, but that fact may be presented as positive for a specific human-readable presentation. This would be accomplished with a negated label. More information on defining concept labels is located in Section 6.2.2.1.</div>
<div class="tdh_066">In addition, presentation linkbases further aid in hierarchical rendering by specifying the indent levels (depth) of the concepts involved in that presentation. This is what creates the visual &#8220;tree&#8221; depiction of the presentation and its hierarchy of concepts.</div>
<div class="tdh_066">Presentations are also closely related to the definitions linkbase (described subsequently). In conjunction with the definitions linkbase, presentations describe the inclusion or exclusion of particular taxonomy-defined dimensions in rendering the presentation.</div>
<p class="tdh_032">2.4.3.2.2     Calculation Relationships</p>  

<div class="tdh_066">Calculation linkbases define mathematical relationships among concepts. This allows values appearing in XBRL instance documents to be checked for consistency by XBRL software. A calculation linkbase provides basic validation rules for instance documents created using the taxonomy to which the calculation linkbase is associated. Like the presentation linkbase, calculation relationships are hierarchical such that all concepts belonging to a calculation arc are added to or are subtracted from one another. In this way, a higher-level concept can become the result of a predefined mathematical calculation (Figure 2-16).</div>
<p><!-- Field: Page; Sequence: 36 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->31<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_099"><img class="tdh_150" src="http://files.xbrl.us/images/tdh/tdh_p1_018.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref9944804"></a>Figure 2-16. An example calculation relationship</p>  

<p class="tdh_032">2.4.3.2.3     Definition Relationships</p>  

<div class="tdh_066">Definition linkbases provide another way to define relationships between concepts. A variety of arcs may be included in a definition linkbase, such as arcs to indicate one concept is a specialized version of another or to require the use of one concept should another be used. These arcs can be custom-defined or commonly used. Standard relationships defined by a definition linkbase are discussed in Section 3.4.3.3.</div>
<div class="tdh_066">Definition linkbases are closely related to presentation linkbases. Definitions define the taxonomy-defined dimensions that are allowable within a presentation through its hypercube definitions. Hypercubes, which are multidimensional data structures, can include or exclude particular dimensions or be <i>open</i> or <i>closed</i>. More information on hypercubes is discussed in Section 3.5.5.</div>
<p class="tdh_032">2.4.3.2.4     Label Linkbase</p>  

<div class="tdh_066">The label linkbase associates human-readable text with machine-readable concept names. This XML document contains various labels for the concepts within the taxonomy and explains how to use and interpret these labels. The usage of these labels is defined by linking concepts to them through the <i>concept-label</i> arc.</div>
<p class="tdh_032">2.4.3.2.5     Reference Linkbase</p>  

<div class="tdh_066">The reference linkbase creates arcs through the concept-reference link that associates a concept with additional information. This additional information may be derived from an authoritative body and provides further understanding to what a concept is meant to represent. The references often function by linking concepts to external regulations and standards or by providing additional meaningful documentation.</div>
<p class="tdh_032">2.4.3.2.6     Formula Linkbase</p>  

<div class="tdh_066">The formula linkbase creates filters and arcs between concepts that specify mathematical relationships beyond a calculation relationship. For more information on using XBRL formulas, see the <a href="https://specifications.xbrl.org/spec-group-index-formula.html"><span class="tdh_035"><i><u>XBRL Formula Specification</u></i></span></a>.</div>
<p class="tdh_020"><span class="tdh_024">2.4.4     </span>XBRL Instance Documents</p>  

<div class="tdh_066">The XBRL instance document, also called the XBRL report, is an instantiation of a taxonomy. This document contains the data that is to be transported and reported. Additionally, though, it contains the definitions for the core dimensions <i>except </i>the concept core dimensions (which are defined in the taxonomy itself). Because the usage and what these XBRL dimensions are meant to represent is</div>
<p><!-- Field: Page; Sequence: 37 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->32<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">included in the <a href="https://specifications.xbrl.org/work-product-index-group-base-spec-base-spec.html"><span class="tdh_035"><i><u>XBRL Specification</u></i></span></a>, they are included in the instance document. In addition, these dimensions are likely to change from report to report. They are not inherent to the taxonomy itself but rather to the particular data set being reported in XBRL. For example, while all XBRL instance documents using a taxonomy to report financial assets may use a concept core dimension named ReportedAssets, the reporting period and entity will vary. Therefore, these XBRL dimensions are defined in the instance document, as they belong to the report, not the taxonomy (Figure 2-17).</div>
<p class="tdh_099"><img class="tdh_134" src="http://files.xbrl.us/images/tdh/tdh_p1_019.jpg" alt="A screenshot of text Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref10019795"></a>Figure 2-17. The XBRL taxonomy versus an XBRL instance document and what each contains</p>  

<div class="tdh_066">The taxonomy should contain the constructs necessary and available to every preparer using that taxonomy, which includes all concept core dimensions, all taxonomy-defined dimensions, all custom data types, and all required concept-based relationships.</div>
<div class="tdh_066">The next chapter will describe the basic XBRL constructs used in a taxonomy and how they map onto an example data model before exploring how to represent that data model in XBRL.<a name="a_Ref9598719"></a><a name="a_Ref9598699"></a><a name="a_Ref9514502"></a><a name="a_Ref9514490"></a><a name="a_Ref8723396"></a></div>
<p><!-- Field: Page; Sequence: 38 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->33<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt; float: right; margin: 8px; border: 1px solid #e2e2e2; border-bottom: none;"><a href="#toc">Table of Contents</a></div>
<div class="tdh_028"><a name="a_Toc24107534"></a><a name="a_Toc23337680"></a><a name="a_Ref17796150"></a><a name="a_Ref16061252"></a><a name="a_Ref16061240"></a>3   Structuring Data</div>
<div class="tdh_027"><a name="a_Toc24107535"></a><a name="a_Toc23337681"></a>3.1   Introduction</div>
<div class="tdh_066">Data can be structured in a variety of ways, from simple spreadsheets, lists, and tabular formats that may have a handful of data points, to complex networks and relational databases that could contain thousands of discrete bits of information. Every data model, from the most simplistic to the most complicated, has structure that provides rules for understanding its data and how the data points relate to one another. That structure, which should be dictated by the nature of the data itself, serves as a guide in leveraging XBRL&#8217;s constructs to appropriately organize the data for transport and consumption.</div>
<div class="tdh_066">A data model is an abstract model that organizes elements of data and standardizes how they relate to each other as well as to real world entities. A robust data model should be able to uniquely identify data points regardless of the data point&#8217;s content, and an XBRL implementation requires data points to be uniquely identified. This section describes how to take a data model and express that model using XBRL constructs. First, various data models are examined so that readers can become familiar with identifying data dimensionality and how data points are affected by the different ways of expressing that dimensionality. After exploring these examples, the chapter turns to how those data models can be expressed in XBRL.</div>
<div class="tdh_066">It is important to note that the intent of XBRL is to provide a structured, predictable data format. This is its major goal, to allow for easy comparability of data across reporting entities. Therefore, while there are always multiple ways to construct a data transport model, that model must adequately represent a multitude of incoming business data models. This can be challenging, so this section also provides a discussion of the multiple approaches to modeling data, some advantages and disadvantages inherent to each, and explores when and why certain situations warrant a particular modeling method.</div>
<div class="tdh_027"><a name="a_Toc24107536"></a><a name="a_Toc23337682"></a>3.2   Typical Data</div>
<div class="tdh_066">In a typical data set, data points are unique, but uniqueness may be through implied data model dimensions. For example, most reports have at least an implicit time period. As a first step in designing an XBRL taxonomy, developers should examine their data set and determine if all pertinent data points can be expressed uniquely.</div>
<div class="tdh_066">What does it mean to be unique? In a relational data model, a set of values, sometimes called a <i>key</i>, in a combination of data dimensions, serves to uniquely identify a data point. No two data points in the model can have the same combination of key values. In more complex models, data dimensions themselves may have further identifying or relational information that is specified elsewhere. For example, a company name may be a dimension that helps add contextual information to sales numbers, but the company may have a government-issued identifier related to them.</div>
<div class="tdh_066">The following sections examine various complexities of data models and their implications for XBRL development. The first section explores a series of simple data points with increasing complexity in relationships, along with methods of organizing the data within XBRL dimensional constructs.</div>
<p class="tdh_020"><a name="a_Ref22830393"></a><span class="tdh_024">3.2.1     </span>Non-relational Data</p>  

<div class="tdh_066">Non-relational data refers to data points that have no semantic relationships beyond a grouping that is implied by the data set itself, such as a reporting entity or a time period. For example, customer names assembled in a list have no relationship with each other beyond the list itself. Removing the list container from these items removes the semantic meaning they hold with each other.</div>
<p class="tdh_046"><img class="tdh_175" src="http://files.xbrl.us/images/tdh/tdh_p1_table_31.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref6490393"></a><a name="a_Ref6490400"></a>Table 3-1. Simple non-relational data</p>  

<p><!-- Field: Page; Sequence: 39 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->34<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">In a non-relational data set (Table 3-1), each item is unique simply by virtue of the fact it is different from every other item. There cannot be duplicate items. In this example, if two customers had the same name, a data dimension could be added to differentiate them, probably through the use of a unique identifier, such as a tax ID or other identification number.</div>
<p class="tdh_020"><span class="tdh_024">3.2.2     </span>Simple Relational Data</p>  

<div class="tdh_066"><a name="c3_data_model"></a>A simple relational data model (Table 3-2) is one where data points have one significant relationship with each other. Building on the non-relational customer list, if one data dimension is added, such as the number of widgets each customer purchased, the data points now have further semantic context. Each data point is now uniquely defined by both the customer name and the number of widgets sold.</div>
<p class="tdh_046"><img class="tdh_177" src="http://files.xbrl.us/images/tdh/tdh_p1_table_32.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref23241120"></a>Table 3-2. Widget data set (simple relational data with independent dimensions)</p>  

<p class="tdh_026">3.2.2.1     Independent Dimensions</p>  

<div class="tdh_066">Two data dimensions are considered independent when they have no semantic relationship with each other. In other words, the meaning of one data dimension has no bearing on the meaning of the other dimension. In this case, the Customer Name has no semantic relationship with the Widgets Sold. The table represents a simple two-dimensional structure, one that could be visualized using X and Y axes to represent the Customer Name and Widgets Sold dimensions, respectively. Independent dimensions are also sometimes referred to as being orthogonal to each other.</div>
<p class="tdh_020"><a name="a_Ref19538499"></a><span class="tdh_024">3.2.3     </span>Complex Data Relationships</p>  

<div class="tdh_066">Complex data relationships add even further dimensionality to the data model. In the customer list example, if a third data dimension is added to express the type of widget purchased, each data point is now defined by three dimensions: Customer Name, Widgets Sold, and Widget Type (Table 3-3).</div>
<p class="tdh_046"><img class="tdh_176" src="http://files.xbrl.us/images/tdh/tdh_p1_table_33.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref6490763"></a>Table 3-3. Widget data set (complex data with independent dimensions in a one-to-one relationship)</p>  

<div class="tdh_066">Importantly, each one of the data dimensions in the example is independent of the other dimensions. In the example above, the Customer Name has no bearing on the Widgets Sold and the Widget Type. Any customer can buy any number of widgets of any type. Furthermore, the number of Widgets Sold is also independent of the Widget Type. If multiple dimensions are required to express a data point uniquely, this does not necessarily imply those data dimensions are dependent on each other.</div>
<div class="tdh_066">Looking at the data, every customer has only one widget type purchased. This is a <i>one-to-one relationship</i>, but the data may not be constrained to a relationship this simple. For example, suppose Bob Green also purchased 100 Circular Widgets. The table would appear as it does in Table 3-4.</div>
<p class="tdh_046"><img class="tdh_178" src="http://files.xbrl.us/images/tdh/tdh_p1_table_34.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref6491083"></a>Table 3-4. Widget data set (complex data with independent dimensions in a one-to-many relationship)</p>  

<p><!-- Field: Page; Sequence: 40 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->35<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">The data points &#8220;750&#8221; and &#8220;100&#8221; require <i>both</i> the Customer Name and the Widget Type dimensions in order to be unique. This becomes the data point&#8217;s unique key. Widget Type must be present with Customer Name to create unique data points in the example. This is now a <i>one-to-many relationship</i>, where each customer can have purchased multiple different types of widgets. The one-to-many relationship exists between the customer and the combination of the Widgets Sold and the Widget Type.</div>
<div class="tdh_066">Removing the Widget Type dimension produces two rows identified with only &#8220;Bob Green&#8221; and are thus non-unique and semantically indistinguishable. For numeric values, the mathematical combination of a set of data points can simulate uniqueness if a necessary key dimension has been removed. For example, Bob Green could be listed with 850 widgets sold. This restores uniqueness with the loss of some information (how many of each widget type comprises the sum).</div>
<p class="tdh_026">3.2.3.1     Dependent Dimensions</p>  

<div class="tdh_066">Dimensions in a data model are dependent upon one another when the value of one dimension influences the values in another. The two dimensions are then semantically related. Suppose a dimension is added to reflect the price per widget for each widget type as it does in Table 3-5.</div>
<p class="tdh_046"><img class="tdh_107" src="http://files.xbrl.us/images/tdh/tdh_p1_table_35.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref6491119"></a>Table 3-5. Widget data set (complex data with both independent and dependent dimensions)</p>  

<div class="tdh_066">The new Price Per Widget data dimension is dependent on the Widget Type. Circular widgets are always priced at $5, rectangular at $10, and triangular at $20 per widget, regardless of customer. Thus, the Price Per Widget data dimension is dependent on only Widget Type. To properly define a data point for Widgets Sold requires three dimensions: Customer Name, Widget Type, and Widgets Sold. Price Per Widget is not necessary, and in fact, should not be used, to make the data point unique.</div>
<div class="tdh_066">If customers have special pricing, however, Price Per Widget becomes dependent on the combination of Customer Name and Widget Type. This example does not indicate this explicitly, but possibilities like these should be considered when designing a data model. In this case, Widgets Sold is still uniquely identified by the same three dimensions as above. However, the price changes based on the customer.</div>
<div class="tdh_066">If the pricing varies for any individual purchase, the model gains a <i>many-to-many relationship</i>. Consider Table 3-6 as follows:</div>
<p class="tdh_046"><img class="tdh_109" src="http://files.xbrl.us/images/tdh/tdh_p1_table_36.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref6491243"></a>Table 3-6. Widget data set (complex data with both independent and dependent dimensions in a<br />
many-to-many relationship)</p>  

<div class="tdh_066">Now the Widgets Sold data point requires four dimensions in order to have a unique key. Jane Doe has purchased a total of 550 triangular widgets, but 350 of them were discounted. Thus, the data point for Widgets Sold requires a combination of the Customer Name, the Widgets Sold, Widget Type, and now Price Per Widget. However, Price Per Widget may still be dependent on Widget Type, Customer Name, or both.</div>
<p><!-- Field: Page; Sequence: 41 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->36<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Dependent dimensions commonly occur in data models, but they can make unique keys very difficult to glean from only examining the data. These relationships should be carefully thought out during the design of any complex relational data model.</div>
<div class="tdh_027"><a name="c3_XBRL_data_model"></a><a name="a_Toc24107537"></a><a name="a_Toc23337683"></a><a name="a_Ref6480590"></a>3.3   Creating an XBRL Data Model</div>
<div class="tdh_066">The basic construct in XBRL for expressing data relationships in a data set is the XBRL dimension. At a fundamental level, an XBRL fact must have a concept core dimension, a period core dimension, an entity core dimension, and it may have either a unit core or a language core dimension as applicable. As the data model increases in complexity, taxonomy-defined dimensions can be added to express the additional relationships relative to the fact. There is no limit to the number of taxonomy-defined dimensions that can intersect with an XBRL fact. However, good taxonomy and data model development practice should guide the developer in producing the fewest number of XBRL dimensions to accurately represent the relevant semantic information.</div>
<div class="tdh_066">The next sections will explore how to represent the previous widget examples in XBRL using XBRL dimensions. Note for the sake of simplicity and brevity, concept and taxonomy-defined dimension names in this chapter are not entirely complete or sufficient for use in an actual XBRL taxonomy. Quite often the suffix has been omitted. For a more complete example of how to properly name concepts and XBRL dimensions, see Chapters 5 and 6.</div>
<div class="tdh_066">The first step in expressing a data set in XBRL is to identify that data set&#8217;s dimensions and how those dimensions translate to XBRL core and taxonomy-defined dimensions. It is important to note that all reports may have implicit XBRL dimensions associated with them that may not be directly represented in a data set. This may include the entity core dimension, the period core dimension, and the unit or language core dimensions. These must be represented in XBRL even if they are not explicit in the originating data set. In the examples that follow, the entity, period, and unit dimensions are combined and represented by a Report Dimension. This is done to simplify the examples because these dimensions are constant for every fact in the data.</div>
<p class="tdh_020"><span class="tdh_024">3.3.1     </span>Representing Non-relational Data</p>  

<div class="tdh_066">At first glance, it may seem that representing non-relational data, such as the list of customer names in Section 3.2.1, should be a simple task in XBRL. However, it quickly becomes obvious that maintaining XBRL fact uniqueness in this situation becomes complicated given the lack of other dimensions to help identify facts and the multiple design choices to overcome this.</div>
<div class="tdh_066">Once again, consider the non-relational data set in Table 3-1. There is a single dimension: Customer Name. The XBRL implementation could look as it does in Figure 3-1.</div>
<p><!-- Field: Page; Sequence: 42 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->37<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_099"><img class="tdh_144" src="http://files.xbrl.us/images/tdh/tdh_p1_020.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref23241457"></a>Figure 3-1. An XBRL data model for non-relational data with non-unique facts<a class="tdh_040" href="#note_ftn2" name="note_ftnref2">2</a></p>  

<div class="tdh_066">The single dimension is represented by the concept core dimension CustomerName. However, this results in non-unique facts for each customer name. There is no semantic variation to differentiate one fact from another as the concept core dimension and the Report Dimension are constant for every fact. This is a poor XBRL implementation of the data set.</div>
<div class="tdh_066">There are two possible solutions to this problem. The first would be to change the concept core dimension from CustomerName to CustomerNameList and to change its data type to be the entire list of names. The fact then becomes the list itself, and there is just one unique fact rather than a series of non-unique facts. Depending on the purpose of the data model, this may an adequate solution with low complexity. However, it does not permit each of the customers to be uniquely identified.</div>
<div class="tdh_066">The second approach is more complicated but provides greater access to the data within the model. Rather than express the data with only a concept core dimension, a taxonomy-defined dimension can be utilized to disaggregate the customer name list. Consider Figure 3-2:</div>
<p class="tdh_099"><img class="tdh_136" src="http://files.xbrl.us/images/tdh/tdh_p1_021.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref13477033"></a>Figure 3-2. An XBRL data model for non-relational data with a taxonomy-defined dimension and unique facts</p>  

<hr class="tdh_260" align="left" size="1" />
<p class="tdh_072"><a class="tdh_040" href="#note_ftnref2" name="note_ftn2">2</a> Note that the core dimensions (Entity, Period, Unit, etc.) are constant for every data point in the model. The Report* dimension on the following figures represents this dimension.</p>  

<p><!-- Field: Page; Sequence: 43 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->38<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">The concept core dimension is CustomerName, and a CustomerIdentifier taxonomy-defined dimension has now been added. The CustomerIdentifier dimension could contain a meaningful unique identifier for each customer if this data exists and is relevant, or it can contain simply the customer name again (which does add redundancy but is an easy approach), or, finally, it can contain an arbitrary identifier. Arbitrary identifiers are analogous to keys in database design or data modeling. This topic will be discussed in greater detail in a later section.</div>
<div class="tdh_066">Now, with this design, each data point can be uniquely expressed as an XBRL fact.</div>
<p class="tdh_026">3.3.1.1     Representing Relational Data</p>  

<div class="tdh_066"><a name="c3_independent_dimension"></a>Creating relational data in XBRL is simple once the appropriate data dimensions have been defined. The example in Table 3-3 provides a simple model. There are dimensions for this table: the Customer Name and the Widgets Sold. Each of these dimensions describes different types of information but they are both related to the Customer. As stated above, these data dimensions are independent of one another.</div>
<p class="tdh_099"><img class="tdh_135" src="http://files.xbrl.us/images/tdh/tdh_p1_022.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref23241611"></a>Figure 3-3. An XBRL data model for relational data with a concept core dimension and a taxonomy-defined dimension</p>  

<div class="tdh_066">The model (Figure 3-3) uses CustomerName as a taxonomy-defined dimension and WidgetsSold as a concept core dimension. More independent XBRL dimensions can easily be added to this model. For example, the dimension WidgetType can be added as either a concept core dimension or a taxonomy-defined dimension. Implementing it as a concept core dimension enforces a one-to-one relationship with the other concept core dimensions, which in this case includes WidgetsSold.</div>
<p><!-- Field: Page; Sequence: 44 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->39<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_099"><img class="tdh_129" src="http://files.xbrl.us/images/tdh/tdh_p1_023.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref23241632"></a>Figure 3-4. An XBRL data model for relational data with two concept core dimensions and a taxonomy-defined dimension</p>  

<div class="tdh_066">The WidgetType dimension has been added as a concept core dimension (Figure 3-4). Because of this approach, the relationship between WidgetType and CustomerName is now one-to-one. A customer can only have one widget type purchased in the report. This design is adequate for the current data set, but it cannot account for every possible data set in the model.</div>
<div class="tdh_066">To do that, the XBRL implementation must be able to account for the one-to-many relationship between WidgetsSold and the other data dimensions. By making WidgetType a taxonomy-defined dimension, a customer can now have more than one type of widget purchased in a single report (Figure 3-5).</div>
<p class="tdh_099"><img class="tdh_141" src="http://files.xbrl.us/images/tdh/tdh_p1_024.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref23241663"></a>Figure 3-5. An XBRL data model for relational data with a concept core dimension and two<br />
taxonomy-defined dimensions</p>  

<div class="tdh_066">In this way, the XBRL model can represent both of the following data sets in Table 3-3 and Table 3-4: for every value of the concept core dimension WidgetsSold, there exists a unique combination of the taxonomy-defined dimensions CustomerName and WidgetType.</div>
<p class="tdh_026"><a name="c3_XBRL_dependent_dimension"></a><a name="a_Ref21422748"></a>3.3.1.2     Dependent Dimensions in XBRL</p>  

<div class="tdh_066">XBRL does not strictly distinguish between independent and dependent dimensions. In fact, XBRL has no enforcement mechanism; all XBRL dimensions are independent by their nature. A dependent dimension, much like an independent dimension, can be represented by either a concept core dimension or a taxonomy-defined dimension. However, there are ramifications to each design choice. From a use case standpoint, what taxonomy-defined dimensions are combined with other taxonomy-defined dimensions</div>
<p><!-- Field: Page; Sequence: 45 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->40<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">and the relationships among them is extremely important. Taxonomy developers should provide guidance to preparers on which taxonomy-defined dimensions should be used to model dependent dimensions.</div>
<div class="tdh_066">Consider again the example with the Price Per Widget data dimension and a single price per widget type in Table 3-5. The Price Per Widget dimension is dependent on Widget Type. This situation lends itself to representing Price Per Widget as a concept core dimension. The reasoning behind this is simple: for every value of the Widget Type dimension, there is only one value for Price Per Widget. Therefore, in the XBRL model, every combination of the values of the CustomerName and WidgetType dimensions should be linked to a single value in PricePerWidget. This maintains uniqueness. The XBRL implementation would appear as it does in Figure 3-6:</div>
<p class="tdh_099"><img class="tdh_138" src="http://files.xbrl.us/images/tdh/tdh_p1_025.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref23241859"></a>Figure 3-6. An XBRL data model for relational data with two concept core dimensions and two<br />
taxonomy-defined dimensions</p>  

<div class="tdh_066">Of minor note, the Report Dimension has now become an oversimplification since the WidgetsSold concept and the PricePerWidget concept do not have the same unit core dimension (since the former is a count of items and the latter is a monetary value). However, this is a trivial detail, and the single Report Dimension will still be used to keep the example graphically simple.</div>
<div class="tdh_066">This XBRL implementation with a second concept core dimension to represent PricePerWidget introduces problems when the dependent dimension is dependent on more than one other dimension, as is the case in Table 3-6. Here, as discussed before, the Price Per Widget data dimension depends on both the widget type and the customer. From a data modeling standpoint, a taxonomy-defined dimension should be created to represent PricePerWidget as illustrated in Figure 3-7.</div>
<p><!-- Field: Page; Sequence: 46 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->41<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_099"><img class="tdh_133" src="http://files.xbrl.us/images/tdh/tdh_p1_026.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref23241889"></a>Figure 3-7. An XBRL data model for relational data with one concept core dimension and three<br />
taxonomy-defined dimensions</p>  

<div class="tdh_066">The model in Figure 3-7 maintains uniqueness yet allows for distinct values for PricePerWidget with any customer or widget type. Even though in the example the Price Per Widget dimension is dependent upon the widget type and customer name, in the XBRL implementation it is represented as a taxonomy-defined dimension which, like any other taxonomy-defined dimension, is operationally independent in XBRL.</div>
<div class="tdh_066">While this approach is fine from a data modeling standpoint, for practical usage there may be other considerations. XBRL instances are collections of data points with semantic meaning added through XBRL dimensions to become facts. In this example, the fact is the number of widgets sold, as identified through the concept core dimension WidgetsSold, with semantic differentiation added through WidgetType, CustomerName, and the other XBRL dimensions mentioned. Treating PricePerWidget as a taxonomy-defined dimension does maintain uniqueness within the data set and add further semantic meaning to WidgetsSold. However, PricePerWidget might be better consumed as a fact itself. The data model as it stands cannot manage this representation, as the values of PricePerWidget are part of the taxonomy-defined dimension. If these values are to be consumed in a meaningful way, this is not an ideal approach.</div>
<div class="tdh_066">Like before when uniqueness was needed, the solution is to create an arbitrary dimension. This is a dimension that is not present in the originating data set but is necessary to the XBRL implementation. The example data model below employs a new taxonomy-defined dimension called Invoice (Figure 3-8). As a consequence, PricePerWidget can now become a concept core dimension again, which allows facts containing the price per widget information to be a part of the XBRL instance. The Invoice taxonomy-defined dimension is arbitrary to the purpose of the report. In this case, it has a value of 1, but it could have any unique value. It can also be representative of an actual invoice number; this serves the same purpose for this example.</div>
<p><!-- Field: Page; Sequence: 47 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->42<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_099"><img class="tdh_136" src="http://files.xbrl.us/images/tdh/tdh_p1_027.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref6491512"></a><a name="a_Ref23241919"></a>Figure 3-8. An XBRL data model for relational data with two concept core dimensions and three taxonomy-defined dimensions (note that Invoice is an arbitrary XBRL dimension added to maintain uniqueness)</p>  

<p class="tdh_020"><a name="a_Ref7079685"></a><span class="tdh_024">3.3.2     </span>General Process</p>  

<div class="tdh_066">From the examples above, the general process of creating an XBRL implementation from a pre-existing data model can be summarized as follows:</div>
<ol>
<li><span class="tdh_190"><i>Identify dimensions in the pre-existing data set/data model</i> – In most cases, the dimensionality of a data set or data model that is well designed should be obvious. Otherwise, take steps to ensure each data point can be uniquely identified through one or more data dimensions. Again, this is a fundamental property of XBRL, that each fact in the instance document is unique.</span></li>
<li><span class="tdh_190"><i>Identify the data that is to be represented in XBRL </i>– The data that will be consumed should become the XBRL facts. Knowing which data points are consumable and which are contextual will help delineate concept core dimensions and taxonomy-defined dimensions.</span></li>
<li><span class="tdh_190"><i>Determine the minimum number of XBRL dimensions to maintain uniqueness </i>– Though not required by XBRL, the most parsimonious data model should be a development goal. Achieving unique data points through the fewest number of XBRL dimensions reduces data model complexity and increases interpretability for both preparers and consumers.</span></li>
<li><span class="tdh_190"><i>Identify where arbitrary XBRL dimensions are necessary to maintain uniqueness </i>– If there are dependent dimensions within the data model, arbitrary dimensions must be added to maintain uniqueness in XBRL. The values of these dimensions may be derived from the data or external sources. This step may include re-evaluating the data model to include more data dimensions that are not arbitrary to accommodate this situation. Changing the existing model is not always necessary; sometimes arbitrary numbers provide a more parsimonious solution than adding unneeded, irrelevant data. It truly depends on the goals of the data model itself.</span></li>
</ol>
<div class="tdh_066">These are the basic steps to create the model for the XBRL implementation. Additional decisions regarding concept names, data types, extensibility, and other fundamental characteristics of the taxonomy will be required, and these will be discussed in later sections.</div>
<div class="tdh_027"><a name="a_Toc24107538"></a><a name="a_Toc23337684"></a>3.4   Components of an XBRL Data Model</div>
<div class="tdh_066">At this stage, the data model should contain concept core dimensions and taxonomy-defined dimensions that may or may not be related to one another. Given this, how is that model represented by an XBRL taxonomy?</div>
<div class="tdh_066">The data model is the foundation of the XBRL taxonomy. With it, a developer can begin to build an XBRL taxonomy that not only allows for the representation of data but describes the data model.</div>
<p><!-- Field: Page; Sequence: 48 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->43<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_020"><span class="tdh_024">3.4.1     </span>Concept Core Dimensions</p>  

<div class="tdh_066">As part of defining the concept core dimensions, concept properties must be defined. Every concept in the model must have its properties defined, but the properties of concept core dimensions most directly relate to the XBRL facts themselves. Concept properties were previously discussed in Section 2.2.6.2.</div>
<p class="tdh_026"><a name="a_Ref21351830"></a>3.4.1.1     Selecting the Correct Data Type</p>  

<div class="tdh_066">Early in the concept core dimension creation process, the data type for each concept must be determined. Data types can be either defined in the <a href="https://specifications.xbrl.org/work-product-index-group-base-spec-base-spec.html"><span class="tdh_035"><i><u>XBRL Specification</u></i></span></a> or they can be defined in the taxonomy itself. Concepts should use the most restrictive data type possible for the type of information being represented. For example, the PricePerWidget concept core dimension should have a monetary per unit data type, rather than a decimal type. The data type also has a close relationship with the unit core dimension (or the language core dimension, if the data is textual). Again, a monetary data type should use a monetary unit, such as an ISO4217 currency identifier. XBRL does not provide any restrictions on matching data types to unit types. XBRL does, however, provide basic data type checking for facts to ensure the data matches the concept data type. For example, creating a fact with the value of &#8220;9&#8221; using a concept with a floatItemType is valid, but creating a fact with the value of &#8220;9.5&#8221; using a concept with an integerItemType would produce invalid XBRL data.</div>
<div class="tdh_066"><a name="a_Hlt24559031"></a><a name="a_Hlt24559030"></a>Figure 3-9 shows a selection of XBRL data types, how they relate to each other, and applicable unit core dimensions. XBRL has more data types available; see Appendix A.</div>
<p class="tdh_099"><img class="tdh_157" src="http://files.xbrl.us/images/tdh/tdh_p1_028.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref22836556"></a>Figure 3-9. A selection of XBRL data types, their relationship to one another, and their relationship<br />
to the unit core dimension</p>  

<div class="tdh_066">Data types may also be defined within the taxonomy by using an XML or XBRL base data type with restrictions. For example, a concept core dimension that is limited to an enumeration of values can be created by extending the XML base string type with a restriction to specific values. XBRL data types are governed by the XML specification and the <a href="https://specifications.xbrl.org/work-product-index-registries-dtr-1.0.html"><span class="tdh_035"><i><u>XBRL Data Type Registry</u></i></span></a>.</div>
<p class="tdh_020"><a name="a_Ref8731454"></a><span class="tdh_024">3.4.2     </span>Taxonomy-defined Dimensions</p>  

<div class="tdh_066"><a name="c3_taxonomy_defined_dimension"></a>At their core, taxonomy-defined dimensions are simply groups of semantically related concepts. Unlike concept core dimensions, these concepts cannot contain an XBRL fact and therefore should have the abstract property. XBRL supports two different kinds of taxonomy-defined dimensions: typed and explicit.</div>
<p><!-- Field: Page; Sequence: 49 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->44<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">For both kinds, there is a concept that describes the dimension. For example, the abstract concept CustomerName describes the XBRL dimension of customer names, which has been used in the widget examples. In XBRL, these are commonly referred to as <i>axes</i> (as they can be thought of as axes or dimensions within the data set).</div>
<div class="tdh_066">When using a taxonomy-defined dimension, an axis and a value for that axis must be provided. For the CustomerName example, the CustomerName concept is the axis and the value could be JaneDoe. Explicit and typed taxonomy-defined dimensions represent the value in different ways. There are situations where one approach has advantages over the other.</div>
<p class="tdh_026">3.4.2.1     Explicit Taxonomy-Defined Dimensions</p>  

<div class="tdh_066">Explicit taxonomy-defined dimensions use additional abstract concepts for each value of the axis. In the widget example, the abstract concept CircularWidgets represents one widget type in the WidgetType taxonomy-defined dimension. In this way, the allowable values for the domain of the axis are &#8220;explicit&#8221; (defined in the taxonomy or in an extension of the taxonomy). Concepts used to indicate allowable values for explicit taxonomy-defined dimensions are commonly referred to as <i>members</i> because they are members of the set or <i>domain</i> of values the taxonomy-defined dimensions represent. The taxonomy should express the relationship between an explicit taxonomy-defined dimension and its member concepts.</div>
<div class="tdh_066">Because the taxonomy defines all the available concepts, it also defines the available values for an explicit dimension. More concepts can be created to represent subgroupings of domain members. In the widget example, a concept RoundedWidgets could be created to contain CircularWidgets, and a concept AngularWidgets could be created to contain TriangularWidgets and RectangularWidgets. RoundedWidgets and AngularWidgets would both be grouping concepts, and CircularWidgets, TriangularWidgets, and RectangularWidgets would be member concepts. Furthermore, a concept may be created that represents the entirety of a dimension&#8217;s values. This is referred to as a domain concept (which typically has a suffix of &#8220;Domain&#8221;).</div>
<div class="tdh_066">If the taxonomy allows extension concepts, then by default all explicit taxonomy-defined dimensions allow extension concepts. A developer may add additional validation on any system using XBRL to enforce extension usage.</div>
<p class="tdh_026">3.4.2.2     Typed Taxonomy-Defined Dimensions</p>  

<div class="tdh_066">Typed taxonomy-defined dimensions use a data type to determine the allowable values of the axis (hence the name &#8220;typed&#8221; dimensions). Typed dimensions do not use concepts as members to indicate allowable values. The data type used for a typed dimension may be simple or complex. Using the widget example, the Price Per Widget data dimension could be represented using a typed taxonomy-defined dimension whose data type is monetary. Likewise, the Customer Name dimension could be a typed taxonomy-defined dimension with a data type of string.</div>
<div class="tdh_066">Rather than specifying a taxonomy-defined dimension and concept member as part of an XBRL context, the XBRL context would designate a taxonomy-defined dimension and a value allowable by the data type of that dimension.</div>
<div class="tdh_066">Depending on the type, typed taxonomy-defined dimensions can either allow a great number of possible values or a very limited number. A string type could effectively have infinite allowable values. A data type that is an enumeration of values, on the other hand, is constrained. For example, a taxonomy-defined dimension with a type that specifies an enumeration with the values of widget types, such as &#8220;circular&#8221;, &#8220;triangular&#8221;, and &#8220;rectangular&#8221;, would allow only these three values. Note that these values are not concepts. Rather they are data specified inside the XBRL context. This permits greater control over the types of values allowable for the axis, but it also limits user extensibility. The same taxonomy-defined dimension but with a string data type would allow for unlimited widget types, albeit at perhaps reduced comparability.</div>
<p><!-- Field: Page; Sequence: 50 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->45<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Developers should note that relying on too many typed taxonomy-defined dimensions to specify values can make reports overly complex, which can in turn make consuming the data difficult. Taxonomy-defined dimensions should only add dimensionality to data points and should not be used to express data.</div>
<div class="tdh_066">For more discussion on the design ramifications of using typed versus explicit taxonomy-defined dimensions, see Section 5.3.2.2.</div>
<p class="tdh_020"><a name="a_Ref9597316"></a><span class="tdh_024">3.4.3     </span>Hierarchical relationships</p>  

<div class="tdh_066">An XBRL taxonomy contains not only the definition of all concepts and data types but also the relationships among the concepts. XBRL allows for several types of relationships. <i>Presentations</i> describe how each concept is arranged in a tree-like, hierarchical format. <i>Calculations</i> describe how concepts relate to one another mathematically (if there is a mathematical relationship). Lastly, <i>definitions</i> directly indicate the relationship between concepts and taxonomy-defined dimensions (including hierarchical relationships but also beyond this structure).</div>
<div class="tdh_066">XBRL uses XML and xLink to represent its relationships. All XBRL relationships exist between two concepts, which can be core concept dimensions or taxonomy-defined dimensions. Relationships may be further refined or expanded by adding more pair-wise relationships to the same concepts, which can build complex hierarchies. The number of relationships can be very large in a large taxonomy, so in order to view the taxonomy in a more human-friendly format, software is often required.</div>
<p class="tdh_026">3.4.3.1     Presentations</p>  

<div class="tdh_066"><a name="c3_presentation"></a>Presentations are the graphical representation of the hierarchical tree of taxonomy concepts and dictate how XBRL consuming software should depict or render the concepts in relationship to one another. Figure 3-10 contains a subset of a presentation derived from the US GAAP 2017 accounting taxonomy.</div>
<p class="tdh_099"><img class="tdh_146" src="http://files.xbrl.us/images/tdh/tdh_p1_029.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref6572936"></a><a name="a_Ref20227933"></a>Figure 3-10. An example presentation from the US GAAP 2017 accounting taxonomy</p>  

<div class="tdh_066">In Figure 3-10, the hierarchical relationships among the concepts is easy to visualize. XBRL presentations describe what are called <i>parent/child</i> relationships. A concept that is a child of another concept does not inherit any properties or characteristics; rather, this relationship represents a composition relationship. The parent concept is comprised of its children. In other words, the parent concept applies additional semantic meaning or organization to its children concepts. Please note that most taxonomies should follow the <a href="https://xbrl.us/xbrl-reference/style-guide/"><span class="tdh_035"><i><u>XBRL US Style Guide</u></i></span></a>, and therefore should use suffixes to indicate what concepts are structural and therefore abstract.</div>
<div class="tdh_066">Presentation names contain a numeric code for sorting purposes, followed by a type and name (see Section 6.2.2.1.1 for more information). Abstract concepts are indicated in this figure with an &#8220;A&#8221; icon. This presentation is named &#8220;Statements of Income (Including Gross Margin)&#8221;. The root concept</div>
<p><!-- Field: Page; Sequence: 51 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->46<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">IncomeStatementAbstract has a single child concept StatementTable, which represents the relationship between the taxonomy-defined dimensions and the concept core dimensions. The first child of StatementTable is StatementScenarioAxis (which is a taxonomy-defined dimension). The concept StatementScenarioAxis (which is an explicit taxonomy-defined dimension) has three total children: ScenarioUnspecifiedDomain, ScenarioPreviouslyReportedMember, and RestatementAdjustmentMember. Because of the relationship between ScenarioUnspecifiedDomain and the other member concepts (specifically that ScenarioPreviouslyReportedMember and RestatementAdjustmentMember are part of it), ScenarioUnspecifiedDomain represents the entirety of the possible values for StatementScenarioAxis.</div>
<div class="tdh_066">The concept StatementLineItems contains abstract concepts that help organize the concept core dimensions. For example, the IncomeLossFromContinuingOperations concept core dimension is part of the IncomeLossFromContinuingOperationsAttributableToParentAbstract concept, indicating that income loss from continuing operations are attributable to the parent entity.</div>
<div class="tdh_066">Developers should provide presentation information to assist preparers in creating reports. Developers may also allow preparers to create custom presentations, which allows them to rearrange the concepts to describe new, different relationships that may better suit their reporting needs.</div>
<p class="tdh_026">3.4.3.2     Calculations</p>  

<div class="tdh_066">A calculation is a grouping of concept core dimensions that defines a specific mathematical relationship among them. Calculations are organized into a tree-like structure using a summation relationship where the highest level item is comprised of the sum of the constituent items. The constituent items can also be comprised of other items. Calculations should only be defined between concepts with numeric data types. In XBRL, calculations are always represented with this summation relationship. However, weighting can be applied to represent subtraction and multiplication.</div>
<div class="tdh_066">XBRL calculations represent relationships between concepts, which can be created by the developer to represent a variety of mathematical relationships. However, XBRL software can only verify calculations with specific conditions. First, the facts involved in a calculation must have the same taxonomy-defined dimensions, unit core dimension, and period core dimension. In other words, the facts must exist in the same time period with the same semantic dimensionality. Second, the precision of the calculated value is dependent on the precision of its components. Verification may fail due to inconsistent or unpredicted rounding in the component facts.</div>
<p class="tdh_026"><a name="a_Ref9945146"></a>3.4.3.3     Definitions</p>  

<div class="tdh_066">Definitions describe relationships among concepts. Unlike presentation relationships, definitions are not limited by a parent/child relationship between concepts. Rather, XBRL allows four standard types of definition relationships:</div>
<ol>
<li><span class="tdh_190"><i>General-special</i> – This relationship indicates that one concept of a pair is a more specialized form of another concept. For instance, in the widget example, the widget type AngularWidgets can be general (referring to any widget type that has angles), while the widget type TriangularWidgets is more specific.</span></li>
<li><span class="tdh_190"><i>Essence-alias</i> – This relationship indicates that one concept of a pair essentially has the same meaning as the other concept. For example, one reporting entity may use the concept Widgets to refer to its product, and another may prefer the concept Gizmos, but the underlying meaning that these concepts are products is the same. The essence-alias definition reflects a change in terminology rather than semantic meaning.</span></li>
<li><span class="tdh_190"><i>Requires-element</i> – This relationship indicates that the value of one concept is required when the value of the other concept in the pair is present. For example, in the widget report with both concept core dimensions WidgetsSold and PricePerWidget, PricePerWidget requires a value for WidgetsSold.</span></li>
<li><span class="tdh_190"><i>Similar</i>&#8211;<i>tuples</i> – This relationship is operationally the same as the essence-alias definition but reserved for usage with tuples. Tuples are not commonly used.</span></li>
</ol>
<div class="tdh_066">Additionally, the <a href="https://specifications.xbrl.org/work-product-index-group-dimensions-dimensions.html"><span class="tdh_035"><i><u>XBRL Dimensions Specification</u></i></span></a> allows for more definition types. These types are used to define the relationships pertaining to the components of a dimension in XBRL. The definitions exist</div>
<p><!-- Field: Page; Sequence: 52 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->47<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">between a concept and a taxonomy-defined dimension to define the hierarchical relationship between them, and all can be seen in Figure 3-10.</div>
<ol>
<li><span class="tdh_190"><i>Dimension-default</i> – This relationship indicates that the concept is the default value for the taxonomy-defined dimension.</span></li>
<li><span class="tdh_190"><i>Dimension-domain</i> – This relationship indicates that the concept represents the domain of the taxonomy-defined dimension.</span></li>
<li><span class="tdh_190"><i>Domain-member</i> – This relationship indicates that one concept is a member of the domain of the other concept that is part of a taxonomy-defined dimension. This relationship can exist between many concepts. For example, a Northeast member may belong to a GeographicLocation axis, but comprising this Northeast member is a group of northeastern states in the US. These each have the <i>domain-member</i> relationship with the Northeast concept.</span></li>
</ol>
<div class="tdh_027"><a name="a_Toc24107539"></a><a name="a_Toc23337685"></a>3.5   Implementing the XBRL Data Model</div>
<div class="tdh_066">The following sections will use the widget example modified to contain additional data and complexity to demonstrate using XBRL with a complex underlying data model. The data set is as follows:</div>
<p class="tdh_046"><img class="tdh_111" src="http://files.xbrl.us/images/tdh/tdh_p1_table_37.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref7080260"></a><a name="a_Ref7078701"></a>Table 3-7. Widgets purchased with additional data complexity and information</p>  

<div class="tdh_066">For the purposes of this example (Table 3-7), the data set is assumed to be complete (the minimum data set – see Chapter 5 for more information). In other words, all possible reporting situations are accounted for. Following this example, the ramifications of this assumption will be explored. This table describes individual purchases that occurred during a period of time.</div>
<p class="tdh_020"><span class="tdh_024">3.5.1     </span>The Data Model</p>  

<div class="tdh_066">Following the general process steps outlined in Section 3.3.2 might produce a data model for this data set as follows:</div>
<p class="tdh_099"><img class="tdh_149" src="http://files.xbrl.us/images/tdh/tdh_p1_030.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref23242051"></a>Figure 3-11. A data model for the widget information presented in Table 3-7</p>  

<p><!-- Field: Page; Sequence: 53 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->48<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">The Client, Type, and Date columns in Table 3-7 are represented by the taxonomy-defined dimensions CustomerName, WidgetType, and OrderDate (Figure 3-11). The Quantity, Price Per, and Widget Sale Income columns are represented by the concept core dimensions WidgetsSold, PricePerWidget, and WidgetSaleIncome. These specific data points are better represented as concept core dimensions only because they are the data that will likely be the focus of consumers. The taxonomy-defined dimensions add semantic meaning to these data points which also creates uniqueness.</div>
<div class="tdh_066">In creating concept names, it is important to note the names should be self-describing. In other words, the concept name should indicate what the concept semantically represents without supporting information from other concepts. Therefore, in this example, Client has been adjusted to CustomerName and so on. For more information on proper concept naming, see the <a href="https://xbrl.us/xbrl-reference/style-guide/"><span class="tdh_035"><i><u>XBRL US Style Guide</u></i></span></a>.</div>
<div class="tdh_066">Also note that this example contains both an order date (shown as the column Date in Table 3-7) and a report date (which is mentioned above the table in the heading &#8220;as of June 1, 2019&#8221;). Generally, the report date is the period core dimension. From a data modeling perspective, it is preferable to base the period core dimension on the report itself rather than individual data points within the report.</div>
<div class="tdh_066">With a data model designed, the XBRL implementation can begin to take shape.</div>
<p class="tdh_020"><span class="tdh_024">3.5.2     </span>Concepts</p>  

<div class="tdh_066">Given the set of concept core dimensions and concepts belonging to taxonomy-defined dimensions, the developers should define their respective properties. All concepts, no matter their use, should have well-defined properties.</div>
<p class="tdh_026">3.5.2.1     Concept Core Dimensions</p>  

<div class="tdh_066">In the widget example (Table 3-7), there are three concept core dimensions: WidgetsSold, WidgetSaleIncome, and PricePerWidget. Their properties appear in Table 3-8.</div>
<table class="tdh_239" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td class="tdh_225">Property</td>
<td class="tdh_223">WidgetsSold</td>
<td class="tdh_223">WidgetSaleIncome</td>
<td class="tdh_223">PricePerWidget</td>
</tr>
<tr class="tdh_205">
<td class="tdh_005"><b><i>Period Type</i></b></td>
<td class="tdh_006">&#8220;instant&#8221;</td>
<td class="tdh_006">&#8220;instant&#8221;</td>
<td class="tdh_006">&#8220;instant&#8221;</td>
</tr>
<tr>
<td class="tdh_213"><b><i>Abstract</i></b></td>
<td class="tdh_215">&#8220;false&#8221;</td>
<td class="tdh_215">&#8220;false&#8221;</td>
<td class="tdh_215">&#8220;false&#8221;</td>
</tr>
<tr class="tdh_205">
<td class="tdh_005"><b><i>Nillable</i></b></td>
<td class="tdh_006">&#8220;false&#8221;</td>
<td class="tdh_006">&#8220;false&#8221;</td>
<td class="tdh_006">&#8220;false&#8221;</td>
</tr>
<tr>
<td class="tdh_213"><b><i>Substitution Group</i></b></td>
<td class="tdh_215">&#8220;item&#8221;</td>
<td class="tdh_215">&#8220;item&#8221;</td>
<td class="tdh_215">&#8220;item&#8221;</td>
</tr>
<tr class="tdh_205">
<td class="tdh_005"><b><i>Data Type</i></b></td>
<td class="tdh_006">&#8220;positive integer&#8221;</td>
<td class="tdh_006">&#8220;positive monetary&#8221;</td>
<td class="tdh_006">&#8220;positive per widget&#8221;</td>
</tr>
<tr>
<td class="tdh_213"><b><i>Balance Type</i></b></td>
<td class="tdh_215">N/A</td>
<td class="tdh_215">N/A</td>
<td class="tdh_215">N/A</td>
</tr>
</tbody>
</table>
<p class="tdh_106"><a name="a_Ref18932800"></a>Table 3-8. Properties for concept core dimensions in the widget example</p>  

<div class="tdh_066">For the properties that must be defined, all three of these concepts have a <i>period type</i> property of &#8220;instant,&#8221; since these data values describe information at a particular time. Even though the table shows a report over a period of time, each individual data point occurred at a specific time. This is an important distinction to make because considering these data points as related to a duration of time, which may make sense from a human perspective, misrepresents them at the level of the data model. This also means these concepts must intersect with a period core dimension that is also defined for an instant, rather than a duration.</div>
<div class="tdh_066">All of these concepts must also have &#8220;false&#8221; defined as their <i>abstract</i> property, since these are concept core dimensions. All three concepts have a value of &#8220;false&#8221; for <i>nillable</i>, since this data model does not permit missing values. Should the model allow missing values, some concepts could have a value of &#8220;true&#8221; for nillable. Nillable concepts allow for great flexibility and extensible dimensionality as they differentiate between a data point that is empty versus one that does not apply. Finally, all concept core dimensions must have &#8220;item&#8221; as the value for their <i>substitution group</i> property. This indicates what type of concept this concept is.</div>
<p><!-- Field: Page; Sequence: 54 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->49<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">The previously discussed properties are the same for these three concept core dimensions. However, for some properties, there are important differences, most notably the <i>data type</i>. WidgetsSold has a data type of &#8220;positive integer.&#8221; This makes sense, since no client has or should have a negative number or a total of zero widgets purchased. WidgetSaleIncome has a monetary data type, since it is a monetary amount. It may be useful to note that this data type does allow for negative monetary amounts. In the case of this example, negative monetary amounts are not possible, so to properly account for this, a taxonomy-defined data type would need to be employed. It is generally a good idea to constrain data types to the set of allowable values as much as is feasible while still accounting for extensibility as necessary. Again, extensibility and its ramifications will be discussed later. For now, a data type of &#8220;positive monetary&#8221; will be added to the taxonomy to reflect monetary values that cannot be negative.</div>
<div class="tdh_066">Finally, the data type for the PricePerWidget concept is somewhat complicated. As it is a monetary value per an item, it could simply be expressed as a decimal. However, a custom-defined data type lends better interpretability and clarity for consumers, even if that data type is not actually more restrictive than decimal. Again, the values for this concept cannot be negative in this data set, so a constraint on that custom-type of positive values only makes sense. This custom data type will be called &#8220;positive per widget&#8221;.</div>
<div class="tdh_066">The final property to address is <i>balance type</i>. This property relates to the accounting principle of debits and credits. For this example, this property can be ignored.</div>
<p class="tdh_026">3.5.2.2     Taxonomy-defined Dimensions Directly Derived from the Data Model</p>  

<div class="tdh_066">In the widget example, there are three taxonomy-defined dimensions: WidgetType, OrderDate, and CustomerName. Note that these are not the only taxonomy-defined dimensions necessary to represent our data model, but these are the ones immediately evident from the columns in Table 3-7. In XBRL, it is best to name concepts such as these with the word &#8220;axis&#8221; as a suffix to the name. WidgetTypeAxis, OrderDateAxis, and CustomerNameAxis become concepts representing an XBRL dimension of data, so their properties are all the same. Because they are concepts representing taxonomy-defined dimensions, they are all abstract. These concepts symbolize a dimension or axis of data; therefore, their substitution group property is &#8220;dimension&#8221;.</div>
<div class="tdh_066">All taxonomy-defined dimensions represent a dimension of the data model. However, multiple supporting concepts may be required for explicit taxonomy-defined dimensions. For example, the WidgetTypeAxis concept represents the dimension of widget types. Another concept is necessary to represent each individual type of widget. Adding RectangularMember, TriangularMember, and CircularMember as supporting concepts of the WidgetTypeAxis taxonomy-defined dimension increases the number of taxonomy-defined dimensions in the model to six. These new concepts have the domain type for their data type, indicating that they are part of a domain of data. Their substitution group property is &#8220;item&#8221; and, like all concepts derived from a taxonomy-defined dimension, they are abstract.</div>
<div class="tdh_066">Unlike WidgetTypeAxis which has members, OrderDateAxis and CustomerNameAxis are typed taxonomy-defined dimensions. This development choice was made because WidgetTypeAxis has set values prescribed by the nature of the data as presumably Widgets, Inc. has a limited, well-defined set of possible widget types, suggesting WidgetTypeAxis be an explicit dimension. OrderDate<span class="tdh_201">A</span>xis and CustomerNameAxis, on the other hand, are more open-ended. If these were explicit taxonomy-defined dimensions, they would require extensibility in order to represent all possible use cases (such as a customer or purchase date not already included in this data set). Extensibility is discussed in Section 3.6.</div>
<p class="tdh_026">3.5.2.3     Supporting Taxonomy-defined Dimensions</p>  

<div class="tdh_066">In order to represent the collection of the taxonomy-defined dimensions applied to this presentation, a <i>hypercube</i> concept is required (hypercubes are sometimes simply referred to as &#8220;cubes&#8221;). This concept, WidgetsSoldByCustomerTable, represents the high-level relationship between the different dimensions of the data. This is considered a hypercube since it is a dimension of dimensions. This XBRL construct serves the important purpose of organizing taxonomy-defined dimensions in a meaningful way. The substitution group property of this concept is &#8220;hypercube&#8221;.</div>
<p><!-- Field: Page; Sequence: 55 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->50<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Additionally, all presentations must stem from a root concept that represents the entirety of the presentation. For this example, that concept will be called WidgetsSoldAbstract. The concept&#8217;s <i>substitution group</i> property is &#8220;item&#8221; and because this concept represents the container concept of the entire presentation, it is abstract.</div>
<div class="tdh_066">Other supporting taxonomy-defined dimensions can be added as necessary to logically aggregate and organize the XBRL dimensions. These can help add semantic interpretability and usability. For example, in this presentation, a supporting taxonomy-defined dimension of Report can be added to group the line items (concept core dimensions) together. This Report abstract concept is not required, but it serves to clearly delineate the concept core dimensions from the taxonomy-defined dimensions. Finally, when using taxonomy-defined dimensions, additional concepts are required to represent the domains of the dimensions. This is true of both explicit and typed dimensions. For this example, that concept is WidgetTypeDomain for the explicit dimension, and the concepts are CustomerNameDomain and OrderDateDomain for the typed dimensions (note these specify the constraining data type for the typed dimensions). For any explicit dimensions, the properties of the domain concept match those of the member concepts of the dimension.</div>
<p class="tdh_020"><span class="tdh_024">3.5.3     </span>The XBRL Presentation</p>  

<div class="tdh_066">Given the concepts defined above, the XBRL presentation can now be defined (Figure 3-12). The presentation makes the hierarchical relationships among the axes and member concepts obvious. It also groups and defines the line items (concept core dimensions) in the report.</div>
<p class="tdh_099"><img class="tdh_151" src="http://files.xbrl.us/images/tdh/tdh_p1_031.jpg" alt="A screenshot of a cell phone Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref7439782"></a>Figure 3-12. An example XBRL presentation for Widgets Sold</p>  

<div class="tdh_066">While this XBRL data model may seem complicated for a simple table, the advantages gained from more concepts outweigh the complexity. The relationships XBRL provides, along with the properties of the concepts, create a data model that is self-describing.</div>
<p class="tdh_020"><span class="tdh_024">3.5.4     </span>XBRL Calculations</p>  

<div class="tdh_066">The widget example in its current form does not have any XBRL calculations that can be defined. Even though Widget Sale Income is a mathematical function of Price Per Widgets and Widgets Sold, XBRL calculations do not permit the weighting within a summation to be derived from a fact. Therefore, Price Per Widgets cannot simply be multiplied with Widgets Sold to verify the facts in Widget Sale Income.</div>
<div class="tdh_066">However, XBRL does offer XBRL formulas that can add this level of validation. See the <a href="https://specifications.xbrl.org/work-product-index-formula-formula-1.0.html"><span class="tdh_035"><i><u>XBRL Formula 1.0 Specification</u></i></span></a> for more information on this topic.</div>
<p><!-- Field: Page; Sequence: 56 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->51<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_020"><a name="a_Ref8733628"></a><span class="tdh_024">3.5.5     </span>XBRL Definitions</p>  

<div class="tdh_066">The XBRL definitions for the taxonomy-defined dimensions appear in Figure 3-13. As a reminder, concept core dimensions (WidgetsSold, WidgetSaleIncome, and PricePerWidget) do not have definitions.</div>
<p class="tdh_099"><img class="tdh_128" src="http://files.xbrl.us/images/tdh/tdh_p1_032.jpg" alt="A screenshot of a cell phone Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref7511672"></a>Figure 3-13. Example XBRL definitions for Widgets Sold</p>  

<div class="tdh_066">The <i>arcrole</i> describes the role of the arc, or connection, between the concepts. The connection between the concepts is very similar to the presentation (Figure 3-12). The XBRL definitions more clearly depict the hierarchical relationships of the dimensions, including the roles of the constituent concepts. In this example, the dimensions have a context in which they can be used (the &#8220;Context&#8221; column), and this can either be <i>segment</i> or <i>scenario</i>. Marking a taxonomy-defined dimension as a segment indicates it contains partial information of a larger piece. For example, each value of the CustomerName taxonomy-defined dimension is a portion of the total data dimension (one customer). Labeling a taxonomy-defined dimension as a scenario indicates that it contains status information about the nature of the data. For example, business facts can be reported as actual, budgeted, restated, pro forma, etc. Using scenarios allows for additional semantic context about the nature of the data being reported. In the widget example, there are no scenario dimensions.</div>
<div class="tdh_066">Within the XBRL definition, the <i>closed</i> property of the hypercube specifies that all taxonomy-defined dimensions in this hypercube must intersect on a fact in order for that fact to be part of this hypercube. If a taxonomy-defined dimension is omitted, the default value for that dimension is assumed to intersect on the fact. If there is no default value, that taxonomy-defined dimension cannot intersect, which will prevent the hypercube from including the fact. An <i>open</i> hypercube removes this constraint. In the widget example, each fact must have the taxonomy-defined dimensions CustomerNameAxis, WidgetTypeAxis, and OrderDateAxis intersecting upon it. For an explicit taxonomy-defined dimension, a dimension-default arcrole allows for a concept to be the default value of the dimension, meaning facts that do not explicitly intersect with that taxonomy-defined dimension are implied to intersect with the default value when rendering the hypercube. If facts do not intersect with a concept member of the taxonomy-defined dimension and that dimension has a dimension-default set, those facts will be considered to intersect with the dimension-default. The dimension-default is usually set to the domain concept, which implies that facts that do not intersect the dimension are a total of that dimension.</div>
<div class="tdh_066">The <i>usable</i> property simply means this domain value is permissible in the hypercube. If the usable property is set to &#8220;false&#8221;, the domain value will be excluded from the domain of valid members for the hypercube. The widget example is straightforward and has no reason to exclude data from the hypercube. A presentation that only applies to a specific widget type could use this property to exclude the unrelated widget types by setting the usable property for those member concepts to &#8220;false&#8221;. When dealing with extensibility, this property is also important.</div>
<p class="tdh_020"><span class="tdh_024">3.5.6     </span>Other Information Necessary for the Taxonomy</p>  

<div class="tdh_066">XBRL requires other information to be defined when developing a taxonomy, such as concept labels and references. However, in developing the data model, these characteristics are not particularly relevant.</div>
<p><!-- Field: Page; Sequence: 57 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->52<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">XBRL preparers will use this information to aid in interpretation of the data model, so this information does represent an important part of taxonomy development. See Section 6.2.2 for more information on these types of characteristics.</div>
<p class="tdh_020"><span class="tdh_024">3.5.7     </span>Ramifications of a Closed Taxonomy</p>  

<div class="tdh_066">The widget example discussed thus far has led to the development of a closed taxonomy. As discussed previously, this means no further concepts can be added to the taxonomy and concepts cannot be reorganized into new or different hierarchical structures. The taxonomy must be employed to represent and report data as-is.</div>
<div class="tdh_066">A closed taxonomy design maximizes data comparability. Every report must contain the same concepts used with the same dimensionality. This makes contrasting one report with another simpler for consumers. However, it limits the ability of preparers to adjust the taxonomy to their own reporting needs. For example, the widget taxonomy as developed can fulfill all the use cases of Widgets, Inc. Should Widgets Co. develop and sell different types of widgets, for example hexagonal widgets, this taxonomy would not be able to address its reporting needs without changing the data model. Widgets Co. cannot represent their information as completely as Widgets, Inc.</div>
<div class="tdh_027"><a name="a_Toc24107540"></a><a name="a_Toc23337686"></a><a name="a_Ref7440704"></a>3.6   Extensibility</div>
<div class="tdh_066"><a name="c3_extensibility"></a>An open, extensible taxonomy can provide ways to address the problem of preparers being unable to represent their data sets fully. Allowing the use of extension concepts and reorganization of the concepts means a preparer could create the concepts needed to express all their data points. As mentioned in the widget example, Widget Co., with their hexagonal widget type which cannot be expressed in the current closed widget taxonomy, could create a hexagonal member of the WidgetType domain. Because XBRL describes the data model as well as the allowable extensions to it, the reports of Widgets, Inc. and Widget Co. are still quite comparable.</div>
<div class="tdh_066"><i>Extensibility</i> allows preparers to &#8220;extend&#8221; the taxonomy to suit their own reporting needs. Extensibility pertains to two major aspects: the ability of preparers to create their own concepts and the ability of preparers to create their own relationships among the concepts already defined in the taxonomy and/or elsewhere. This can become as complex as importing a secondary taxonomy to be used in conjunction with a primary taxonomy.</div>
<div class="tdh_066">Extensibility can be something of a double-edged sword. On the one hand, increased extensibility allows preparers to create reports that may be more reflective of their specific data sets. On the other hand, if reports differ significantly, it can diminish the comparability and interpretability of each one, which somewhat reduces the utility of XBRL overall. Balancing the needs of preparers to create custom concepts and relationships against the needs of consumers in being able to compare standardized and uniform data sets can be a complex topic.</div>
<div class="tdh_066">The advantages, disadvantages, and other considerations concerning taxonomy extensibility will be discussed in the following sections. Generally, in XBRL, there are no provisions to prevent or allow extensibility. Extensibility is determined by the taxonomy developers during the development process and in how the taxonomy is implemented. A preparer can extend the taxonomy any way desired, but if the system that must interpret that taxonomy does not recognize the changes, the use of extensible concepts becomes erroneous. Proper taxonomy development should include guidance for preparers on how to properly extend a taxonomy (see Section 7.4.5).</div>
<div class="tdh_066">There are some methods within XBRL to give precedence to particular relationships, and those will also be covered in Chapter 5. This chapter also provides a more in-depth analysis of the means of providing extensibility and their impacts on comparability.</div>
<p class="tdh_020"><span class="tdh_024">3.6.1     </span>Extending Concepts</p>  

<div class="tdh_066">Creating new concepts, whether they are concept core dimensions or concepts belonging to taxonomy-defined dimensions, necessarily requires defining the relationships the new concept has to the other</div>
<p><!-- Field: Page; Sequence: 58 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->53<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">concepts within the taxonomy. This means that when extension concepts are permissible, extended hierarchies must also be allowed.</div>
<div class="tdh_066">Preparers should not create concepts beyond the scope of the data model. The guidance document should specify this.</div>
<p class="tdh_026"><a name="a_Ref9339332"></a>3.6.1.1     Extending Data Types</p>  

<div class="tdh_066">As discussed previously, XBRL allows extended data types that build upon XML and XBRL data types. Preparers should be discouraged from creating extended data types as the data model should be designed to contain data types to represent all possible data. Because preparers should not create concepts outside the scope of the data model, extended data types will likely not be needed. Developers can of course create custom data types for the taxonomy.</div>
<p class="tdh_026">3.6.1.2     Extending Dimensions</p>  

<div class="tdh_066">Another method of allowing extensibility is derived from the nature of explicit versus typed dimensions. A typed dimension has a specific set of allowed values, whereas an explicit dimension relies on the relationships between concepts to dictate its values. Compare, for example, the taxonomy-defined dimensions of WidgetTypeAxis and CustomerNameAxis as defined in the widget example (Figure 3-12 and Figure 3-13). The WidgetTypeAxis taxonomy-defined dimension requires extended concepts in order to encompass widget types outside of the member concepts (Triangular, Circular, and Rectangular). In contrast, the values for the CustomerNameAxis taxonomy-defined dimension are constrained only by its data type. As stated previously, this design choice makes sense for this data set, where there is just a small, limited number of widget types which are specific and well-defined, but there could be any number of customer names. Because the values for typed dimensions are constrained by a data type, the only method to extend data for a typed dimension beyond its data type is to create a similar dimension to replace it.</div>
<div class="tdh_066">Developers should keep in mind which dimensions of the data model may necessitate extensibility based on possible use cases. If the values are very clearly limited to a particular set, a typed dimension may provide a way to both express all the data while preventing unwanted extensibility. However, a typed dimension with a data type that is too restrictive may cause preparers to replace the dimension which reduces comparability of the data. Likewise, a typed dimension with a data type that is not restrictive enough can have the same end result.</div>
<div class="tdh_066">An explicit dimension, however, affords preparers the ability to create extended concepts that are subsets of taxonomy-defined dimensions. This means preparers can further disaggregate their data as necessary while indicating how that data fits within the standard taxonomy.</div>
<p class="tdh_026">3.6.1.3     Extending Using Label Roles</p>  

<div class="tdh_066">Concepts should have certain defined label roles created by the taxonomy developers. Concept meanings can be extended by allowing the declaration of other label roles by preparers. Extending labels can help human readability and consumers to develop better use case models. However, in order to allow extensible labels, a certain amount of additional extensibility is required. See Section 5.4.2.2 for more information.</div>
<p class="tdh_020"><span class="tdh_024">3.6.2     </span>Other Developed Taxonomies</p>  

<div class="tdh_066">XBRL allows for importing of any taxonomy into any report. Thus, developers should decide which taxonomies, if any, preparers may use. In addition, the developed taxonomy may include other taxonomies by default. All information in the imported taxonomy&#8217;s data model is available for use, including data types. However, any relationships among concepts in each separate taxonomy must be defined by the developer or the preparer. It also should be noted that the hierarchy of a well-known taxonomy (or any taxonomy) does not need to be imported if the developer wishes to provide only new relationships.</div>
<p><!-- Field: Page; Sequence: 59 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->54<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_020"><span class="tdh_024">3.6.3     </span>Custom Taxonomies</p>  

<div class="tdh_066">As an extension to importing well-known taxonomies, preparers may also import custom taxonomies at the developer&#8217;s discretion. This should be allowed with caution as the developer will not maintain any control over the taxonomy at such point. Therefore, poor design choices or other issues may be integrated into the taxonomy without the developer&#8217;s knowledge or consent. This is not a recommended approach.</div>
<div class="tdh_027"><a name="a_Toc24107541"></a><a name="a_Toc23337687"></a>3.7   Moving Forward</div>
<div class="tdh_066">This process of examining sets of data, determining that data set&#8217;s dimensionality, and translating the dimensionality to an XBRL data model must be repeated for all data pertinent to the project. Once this process is complete and the developer has an initial idea of the needs dictated by the data itself, the impact of stakeholders&#8217; needs and use cases can be deeply examined. The next chapter explores these considerations.</div>
<p><!-- Field: Page; Sequence: 60 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->55<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt; float: right; margin: 8px; border: 1px solid #e2e2e2; border-bottom: none;"><a href="#toc">Table of Contents</a></div>
<div class="tdh_028"><a name="a_Toc24107542"></a><a name="a_Toc23337688"></a><a name="a_Ref13047535"></a>4   Assessing Overall Project Scope</div>
<div class="tdh_066">As an initial step to any major project, developers must determine the project&#8217;s <i>scope</i>, that is, the work that must be done to deliver a product with a predetermined set of features and functions. The scope provides an essential foundation that drives the development process. As part of the scope, there are other key considerations. What is the project&#8217;s purpose? How big and complex is the project? How will users and other interested parties interact with the project? What resources, skills, information, and personnel are required to meet the project&#8217;s purpose successfully? Once the project is completed, how are its relevant work products documented, disseminated, and maintained? If changes must be made, who decides when and in what ways to implement them?</div>
<div class="tdh_066">These key questions must be carefully researched and answered before work commences. In this chapter, there will be a discussion of the factors underlying these critical questions to guide developers in assessing their own project needs. Because XBRL projects can vary widely in the ways mentioned above, there is no one answer to some of these questions. The development process may vary considerably in different situations. However, a general series of steps can aid developers in focusing their process and avoiding pitfalls.</div>
<div class="tdh_066">In researching and answering these questions, developers can document their own development process and the taxonomy as it is being created. In addition to maintaining consistent understanding of the taxonomy and its development, maintaining documentation of the development process can lead to parallel writing of public-facing documentation for the taxonomy (such as the <i>Taxonomy Guide</i>), which saves time and work. More information on the <i>Taxonomy Guide </i>and other taxonomy documentation can be found in Chapter 7.</div>
<div class="tdh_027"><a name="a_Toc24107543"></a><a name="a_Toc23337689"></a><a name="a_Ref11415892"></a>4.1   Define the Project&#8217;s Goals</div>
<div class="tdh_066">XBRL presents a unique project perspective. Because it is designed as a data transport model, there will be multiple parties, multiple systems, and possibly even multiple data models involved. At the very least, there are preparers, with their business models for data, and consumers, who use that data to their own ends and may possess their own data models. The originating data model may or may not share any similarity with the consumer model. Also, depending on the scope of the project, there may be many independent preparers and many consumers, and each entity may have entirely different methods and needs concerning their data. In addition, quite often there are regulatory requirements impacting the reporting process. These requirements may stipulate certain types of data be reported, perhaps in standard formats.</div>
<div class="tdh_066">It is the goal of the XBRL taxonomy to facilitate the structured reporting of data from preparer to consumer. Beyond that, the needs of any particular taxonomy and reporting system can vary greatly. They can be:</div>
<ul class="tdh_179">
<li class="tdh_181">Created for public or private data</li>
<li class="tdh_181">Designed to meet regulatory compliance requirements or to accommodate industry (non-mandatory) requirements</li>
<li class="tdh_181">Extensible by preparers or the sponsor of the taxonomy can choose not to allow extensions</li>
<li class="tdh_181">Built on a codified standard or based loosely on an existing reporting process</li>
</ul>
<div class="tdh_066">Before starting development, developers should make policy decisions that are most appropriate for the taxonomy. These various policies will impact the structure, content, and use of the data produced by the taxonomy. Policies can be changed later on, but some foundational decisions should be made upfront to help shape the work to be conducted. Topics that should be explored include:</div>
<ul class="tdh_179">
<li class="tdh_181">Extensibility</li>
<li class="tdh_181">Incorporation of industry standards</li>
<li class="tdh_181">Validation requirements</li>
</ul>
<p><!-- Field: Page; Sequence: 61 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->56<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<ul class="tdh_179">
<li class="tdh_181">Structural requirements (for example, when and when not to use taxonomy-defined dimensions versus concept core dimensions)</li>
<li class="tdh_181">Phasing of development (for example, initially the taxonomy will cover a certain set of elements, but it may be expanded at a later date)</li>
<li class="tdh_181">How the data is currently gathered, stored, and/or reported and the impact those systems may have on the taxonomy</li>
<li class="tdh_181">How the data is used by consumers, including the types and structures of data required</li>
</ul>
<div class="tdh_066">Because policies and goals may create subtle consequences in terms of the taxonomy structure or aspects of the development or maintenance plan, it is vitally important that developers begin their process by identifying and qualifying <i>functional requirements</i> and <i>use cases</i>.</div>
<p class="tdh_020"><span class="tdh_024">4.1.1     </span>Defining Functional Requirements</p>  

<div class="tdh_066">At the core of any system, <i>functional requirements</i> specify operations of that system or its components as a furtherance of what that system is meant to accomplish. Functional requirements may involve technical details, data manipulation and processing, calculations, and data modeling. Understanding the functional requirements, what a taxonomy is meant to do at a direct, functional level, will guide the initial development process. XBRL taxonomies are meant to transport data from preparers to consumers, but what purpose is this transport process serving? Is the taxonomy meant to present structured data for easy comparisons among multiple reporting entities? Is it intended to ensure adherence to regulatory guidelines? Is the taxonomy meant to organize data in a specific way as to meet criteria for particular analysis systems? In some cases, taxonomies may need to meet multiple functional requirements, and these purposes must all be addressed during the development process.</div>
<div class="tdh_066">It may also be important at this early stage to differentiate between functional requirements versus <i>non-functional requirements</i>. A functional requirement defines what the system is designed to do, while a non-functional requirement (sometimes also called a quality requirement) imposes a constraint on the system&#8217;s design or implementation. Non-functional requirements may be posed as requests/recommendations and must be weighed carefully in terms of their cost versus their benefit and their impact on the overall taxonomy or its components.</div>
<p class="tdh_020"><span class="tdh_024">4.1.2     </span>Understanding Use Cases</p>  

<div class="tdh_066">Broadly, a <i>use case</i> is a type of requirements specification for a system that represents a list of actions or steps. This list defines interactions between users (sometimes called actors) and the system, to achieve a specific goal. Use cases may help define both functional and non-functional requirements. In terms of XBRL, use cases refer to the ways in which the data represented and transported by XBRL are to be prepared or used. For example, a use case may be a preparer employing the taxonomy to represent a table of financial information for a company. For a consumer, a use case could involve using that financial information in a data model to determine the solvency of that company. Use cases can be simple or complex, and they can directly relate to how the taxonomy itself structures data or how that data is transmitted. They can be directly relevant to the development process, or they can be a secondary consideration with implications that become important under certain circumstances.</div>
<div class="tdh_066">Well-defined use cases typically capture all the possible ways the user and system can interact with each other that result in the user achieving his or her goal. They also capture the challenges that can occur along the way that may prevent the user from achieving the goal. A simple example of this is the question of extensibility. Extensibility was discussed in Section 3.6. If consumer use cases dictate the data be strictly comparable between reports, allowing extension concepts and data types may be contrary to this need as extensibility tends to reduce uniformity in data sets. Because use cases can guide developers in understanding the system they must represent with the XBRL taxonomy, the use cases that apply to the taxonomy must be thoroughly identified before development work can begin.</div>
<p class="tdh_020"><span class="tdh_024">4.1.3     </span>Identifying the Data to Be Transported</p>  

<div class="tdh_066">Tied to developing and understanding use cases is having a good handle on what data needs to be represented by XBRL and transported from a business data model to a consumer data model. Obviously</div>
<p><!-- Field: Page; Sequence: 62 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->57<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">representing dimensional data accurately and parsimoniously is the overarching goal of any XBRL development project.</div>
<p class="tdh_099"><img class="tdh_158" src="http://files.xbrl.us/images/tdh/tdh_p1_033.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref16587657"></a>Figure 4-2. Gathering the documents, forms, databases, and other sources of data involved in creating an XBRL taxonomy</p>  

<div class="tdh_066">Because XBRL represents a data transport model as part of an information supply chain, the data models and data sets involved in that supply chain before and after the XBRL taxonomy is employed, must be analyzed (Figure 4-2).</div>
<div class="tdh_066">The process of identifying and understanding the relevant data sets may involve:</div>
<ul class="tdh_179">
<li class="tdh_181">Exploring databases, the nature of the data they contain, and their relational structures</li>
<li class="tdh_181">Understanding the design and purpose of current relevant forms, such as forms used in reporting information to regulatory agencies or other industry officials</li>
<li class="tdh_181">Understanding current reporting mediums (document or spreadsheet-based reports and underlying systems used to develop them)</li>
<li class="tdh_181">Identifying information crucial to the report (for example, a financial report will likely focus on monetary data with other information becoming contextual whereas a report on manufacturing processes may feature other information with monetary data becoming contextual)</li>
<li class="tdh_181">Reviewing and incorporating instructions and/or guidance on how to prepare required disclosures</li>
<li class="tdh_181">Identifying potentially sensitive information</li>
</ul>
<p class="tdh_075">It is important to note that the taxonomy developers need not be industry experts or experts in the types of data the taxonomy is meant to represent. Also, they may not need to have a deep understanding of data architecture or engineering. However, even if they do not have this knowledge and these skills, these aspects are still are important to bring into the development process. Therefore, in order to fully understand both the range of possible use cases for the XBRL taxonomy and the purpose the taxonomy must serve, developers will need to seek the input and insight of multiple experts and stakeholders.</p>  

<div class="tdh_027"><a name="a_Toc24107544"></a><a name="a_Toc23337690"></a><a name="a_Ref11415912"></a>4.2   Identifying and Engaging Stakeholders</div>
<div class="tdh_066"><a name="c4_stakeholder"></a>A <i>stakeholder</i> refers to an entity with interest or concern in the project. A stakeholder may be comprised of a single person, a group of people, or an entire organization. Stakeholders typically offer key opinions,</div>
<p><!-- Field: Page; Sequence: 63 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->58<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">insight, and experience concerning the nature of the data to be reported and how that reporting process should operate. No single stakeholder likely has the breadth of knowledge, perspective, and understanding to shape the taxonomy; therefore, it is vitally important to engage all relevant parties during the development process (Figure 4-3).</div>
<p class="tdh_099"><img class="tdh_124" src="http://files.xbrl.us/images/tdh/tdh_p1_034.jpg" alt="A picture containing wheel Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref20223807"></a>Figure 4-3. Different stakeholders working together to create a taxonomy</p>  

<div class="tdh_066">For XBRL, stakeholders are typically participants along the information supply chain. Preparers who must use the taxonomy to create reports, regulators who employ the taxonomy to control and monitor structured reporting, data intermediaries who gather information, and consumers of the data that is reported, all represent stakeholders in a typical XBRL development process. Industry experts and data analysts may also offer key insight into how a taxonomy can best structure pertinent data. In the case of US GAAP reporting, for example, accountants who are involved in SEC reporting both from accounting firms and from public companies, filing agents that work with public companies preparing their financials for SEC submission, investors and regulators that use SEC reported data, data intermediaries who may be charged with extracting the data from the taxonomy and presenting it to consumers, and financial reporting software providers may all be important stakeholders.</div>
<div class="tdh_066">Stakeholders are often the parties who provide use cases. Their needs and wants concerning their own interaction with the taxonomy and its reporting system must be considered when deciding how that taxonomy and system should function. This helps keep the taxonomy true to its purpose. When the taxonomy is small and perhaps of limited scope or propriety, engaging stakeholders may be a simple task. However, if the project is large and complex with the capacity to affect multiple different industry sections, identifying pertinent opinions and views may be more challenging. Still, identifying stakeholders before beginning the development process is critical regardless of the size and complexity of the project.</div>
<div class="tdh_066">Particularly during the early stages of taxonomy development, developers should take care to involve stakeholders from all relevant areas of interest in the process. This could mean that at least one stakeholder from each link on the data supply chain (data preparation and consumption, for example) should be represented when determining the initial use cases of the taxonomy. Later, depending on the size and potential impact of the project, a much broader survey of stakeholders and interested parties will be required to obtain an even greater number of points of view to ensure that the taxonomy captures all possible situations.</div>
<div class="tdh_027"><a name="a_Toc24107545"></a><a name="a_Toc23337691"></a>4.3   Define the Scope of the Taxonomy</div>
<div class="tdh_066">Clearly the size and complexity of the taxonomy is also a key topic to explore in the early stages of development. For taxonomies that may only impact a few interested parties (such as a taxonomy that is used internally to a company or between multiple companies within a small industry), the development process might be less complex. Fewer stakeholders could indicate fewer use cases. In addition, if the data to be reported is limited and/or simple, the number of potential use cases could also be small.</div>
<div class="tdh_066">Taxonomies with large data sets or whose influence may reach a large industry or multiple industries may face a significantly more complex development process. In these cases, it is quite common for many stakeholders and use cases to be involved. It logically follows that a large project will also require more</div>
<p><!-- Field: Page; Sequence: 64 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->59<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">resources and a larger scale effort, including increased organization, planning, and coordination. Therefore, determining the size of the taxonomy early in the process is incredibly important.</div>
<div class="tdh_027"><a name="a_Toc24107546"></a><a name="a_Toc23337692"></a><a name="a_Ref11750517"></a>4.4   Identifying Relevant Systems</div>
<div class="tdh_066">Quite often other technologies and technological systems are involved in the information supply chain. These may be systems for storing data, analyzing or interpreting the data, sharing the data, or receiving the data. How XBRL fits into the systems already in place must be explored early in the design process. For example, public companies submitting financial information to US Securities and Exchange Commission may be required to do so in XBRL using the SEC&#8217;s Electronic Data Gathering, Analysis and Retrieval (EDGAR) system. XBRL reports transmitted in this way must be compliant with both the XBRL financial reporting taxonomy required and with the transmission system itself. As another example, a reporting system could be in place for studies at a university to share data with other universities or within the university such as between its internal groups and departments. A new XBRL taxonomy to standardize and structure those reports may have to be compliant with anticipated data formats, the transmission system itself, and with regulatory groups and agencies.</div>
<div class="tdh_066">In addition to considering the systems involved in the transmission of data from preparers to consumers, developers must also examine sources of data themselves. Data can originate from a wide range of systems and formats depending on the preparers&#8217; environments. For example, information pertinent to submitting financial reports to the US SEC may come from Microsoft Word, Excel, Google Docs, internal databases, data management systems, and many other sources. Data from multiple sources and systems may be combined in an XBRL report. Therefore, XBRL developers may want to consider from <i>where </i>the data is coming when deciding how to best model it with XBRL.</div>
<div class="tdh_066">If no formalized system exists, taxonomy developers should also consider what systems may be necessary to support the structured reporting process. This can extend to software solutions that can aid preparers and consumers in using the XBRL taxonomy, which is discussed more in Section 4.6.3.</div>
<div class="tdh_066">The nature of any relevant systems might also guide developers in determining the method of XBRL transport, whether it be XML, JSON, or CSV. For example, if the reports are meant to be human-readable after submission (for example, if they are to be posted to a public space, such as a company website), Inline XBRL might be the best option for a transport method.</div>
<div class="tdh_027"><a name="a_Toc24107547"></a><a name="a_Toc23337693"></a>4.5   Identifying Regulatory or NGO Requirements</div>
<div class="tdh_066">Another important facet to consider early in the development process are <i>regulatory requirements</i>, if applicable. Regulatory requirements, which may come from governmental agencies, non-governmental organizations, industry groups, or internal oversight within the industry, are often a large driving force in determining the taxonomy&#8217;s functional requirements. Also, it is not uncommon for the regulatory agency to sponsor the taxonomy&#8217;s development to ensure inclusion of pertinent rules and regulations within the taxonomy itself. If this is not the case, members of regulatory agencies are often stakeholders and should be consulted during the development process.</div>
<div class="tdh_066">Depending on the number of agencies that oversee the content of the data and the goals of the taxonomy itself, the taxonomy model may be heavily driven by these stakeholders as opposed to preparers and consumers. This is another reason it is vitally important to determine the overall goals and engage stakeholders early in the development process, as stated in Sections 4.1 and 4.2.</div>
<div class="tdh_066">Regulators may also have business or industry rules that can be incorporated into the taxonomy to aid in producing better quality data. Validation rules can specify that certain reported values must always be positive or negative, that certain concepts are required to be reported, or that certain concepts must always, or should never, be reported together. Business rules can be a powerful tool to ensure that data produced is consistently and accurately prepared.</div>
<div class="tdh_027"><a name="a_Toc24107548"></a><a name="a_Toc23337694"></a>4.6   Other Requirements and Considerations</div>
<div class="tdh_066">Once stakeholders have been engaged, and functional, non-functional, and regulatory requirements have been established, other requirements can be considered. These include resources, software, staff, and</div>
<p><!-- Field: Page; Sequence: 65 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->60<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">personnel essential to ensure a comprehensive and successful development process. Depending on the nature of the taxonomy being created and the breadth of the project, meeting other requirements may be a complex task and require significant planning.</div>
<p class="tdh_020"><span class="tdh_024">4.6.1     </span>Resource Requirements</p>  

<div class="tdh_066">Resource requirements necessary in the building of an XBRL taxonomy may be comprised of personnel, funding, software, testing and validation plans, and other tools that can aid in the development process. Again, depending on the scope of the taxonomy and the size of the project, resource requirements may be large and complicated. Personnel with data architecture experience, industry experience, data management specialists, and software engineers with a knowledge of XML may provide useful insight. Project managers and taxonomy developers should identify the necessary resources early in the development process to ensure proper resource scheduling, availability, and optimization.</div>
<p class="tdh_020"><a name="a_Ref11916892"></a><span class="tdh_024">4.6.2     </span>Support Requirements and Governance</p>  

<div class="tdh_066">Building an XBRL taxonomy is truly only the first step in using XBRL as a transport model. Once the taxonomy has been employed by the industry population, it must be maintained and monitored. This is true no matter the scope of the taxonomy. As with most information models, XBRL taxonomies rarely remain static; new regulations, different models being applied to data, and changes in industry standards or the data itself can require alterations in the taxonomy. In addition, use of the taxonomy will help developers identify ways to improve it.</div>
<div class="tdh_066">Therefore, XBRL taxonomies require support and governance. Support requirements may include addressing ease of taxonomy implementation and managing extensibility. They also dictate what sort of systems are necessary to implement future changes and are closely related to governance. <i>Governance</i> refers to the rules, procedures, and controlling entities by which a taxonomy is managed. Taxonomy governance cannot be overlooked; a system for maintaining oversight must be in place to ensure data integrity, validation, and proper usage.</div>
<div class="tdh_066">Governance is an important topic that is covered in Chapter 8.</div>
<p class="tdh_020"><a name="a_Ref10724329"></a><span class="tdh_024">4.6.3     </span>Software Development and Developers</p>  

<div class="tdh_066">As discussed in Section 4.4, different software systems may be involved in data handling through preparation, transmission, and consumption. These systems should be analyzed for their potential impact on the taxonomy. Additionally, XBRL software itself may be considered as part of the development process.</div>
<div class="tdh_066">An XBRL taxonomy alone is an XML specification; it has no inherent functionality to visualize presentations or definitions, import data into or export data from the taxonomy, or ensure proper validation. Because XBRL adheres to XML standards, there is some syntactical validation as well as visualization available in any software package that can parse and represent XML. However, it will not be specific to the taxonomy itself. If there is a need for these sorts of functions, taxonomy developers may need to look into software systems that support such functionality.</div>
<div class="tdh_066">In large industries and domains, such as public companies reporting financial information in XBRL to the US SEC, software vendors already exist and must conform to reporting standards and requirements as part of their business model. Therefore, in this case, supporting software development is in the hands of third-party vendors who must adhere to the taxonomies allowed by the SEC. Dissemination of changes in a predictable, regular, orderly manner is critical. In other situations, software to guide preparers in creating their XBRL report is more tightly monitored and regulated. In a case like this, the taxonomy developers and governance groups must maintain a tight relationship with third-party developers to ensure accurate understanding of the taxonomy. These are two examples in a wide variety of ways in which software developers may interact with taxonomy developers. Of course, in a small reporting environment where the scope of the taxonomy is more limited, taxonomy developers may also be faced with developing their own solutions if tailored presentation viewers, custom data processing, and specific validation is necessary. Again, though, the cost/benefit of these sorts of solutions must be thoroughly assessed.</div>
<p><!-- Field: Page; Sequence: 66 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->61<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Generally, supporting software development falls outside the scope of this document. However, it is vital that taxonomy developers consider what sort of software packages might aid preparers, consumers, and others in understanding how the taxonomy works and how to use it. An XBRL taxonomy is only useful if there are means to create and access XBRL instance data, especially software solutions to guide preparers in producing strong, robust XBRL reports. From a very early development stage, developers should consider identifying what software solutions would be beneficial to taxonomy users and engaging with software developers or undertaking the task themselves to ensure these solutions are or will become available.</div>
<p class="tdh_020"><span class="tdh_024">4.6.4     </span>Documentation and Communication</p>  

<div class="tdh_066">Once a taxonomy has been developed, it must be properly documented. Taxonomies can be extremely complex, with hundreds if not thousands of concepts, and the use of those concepts must be clearly defined. An XBRL taxonomy ideally is self-describing; nothing more than its schema, its linkbases, and any referenced taxonomies should be required to use and understand the taxonomy. That said, the label roles (see Section 2.2.6.4) for each concept help define its uses, and these must be correct and properly documented. In addition, for taxonomies that have a large scope and that are sufficiently complex, guiding documents, such as preparer&#8217;s guides and other supporting information, are important to consider. These are useful tools to preparers, consumers, and other interested parties in understanding the taxonomy, its data types, and the way it represents dimensional information. Having appropriate documentation can aid people of all knowledge and skill-levels as they begin to use XBRL and the newly developed taxonomy.</div>
<div class="tdh_066">Changes to the taxonomy must also be clearly communicated to the taxonomy users and, in some cases, the community at large. This dissemination process should be pre-determined, and generally falls under a discussion of taxonomy governance, which has been discussed briefly in Section 4.6.2 and will be explored thoroughly in Chapter 8.</div>
<p class="tdh_020"><span class="tdh_024">4.6.5     </span>Intellectual Properties</p>  

<div class="tdh_066">Depending on the size and purpose of the taxonomy, there may be legal considerations concerning the tools and information required to develop it. In these cases, developers should safeguard the taxonomy against any future issues by requiring all participants in the development process sign <i>intellectual property (IP) agreements</i>, stating that these participants are freely contributing all work product and comments. For example, when XBRL US holds working groups where development is conducted, an IP statement is read at the start of each call or meeting so that contributors are aware of the bounds in which their contributions will be used. Appendix I shows a sample IP agreement that can be used for this purpose and for the public review which is discussed later in this chapter.</div>
<p class="tdh_020"><span class="tdh_024">4.6.6     </span>Balancing Requirements</p>  

<div class="tdh_066">In the creation of any complex system, there are bound to be disagreements about the goals that must be achieved and the importance of the relative outcomes. Stakeholders, which may include data preparers, data consumers, regulatory agencies, and other interested parties, may each have unique perspectives on the nature of the taxonomy to be developed. However, as discussed previously, no one stakeholder likely possesses the breadth of knowledge and experience to shape the taxonomy in its entirety.</div>
<p><!-- Field: Page; Sequence: 67 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->62<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_099"><img class="tdh_156" src="http://files.xbrl.us/images/tdh/tdh_p1_035.jpg" alt="A close up of a logo Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref20224027"></a>Figure 4-1. Balancing the needs of preparers and consumers while meeting regulatory requirements</p>  

<div class="tdh_066">Once all uses cases, functional requirements, and non-functional requirements are identified, any conflicts that arise from the investigative process should be resolved. For example, it may be the case that preparers face significant time and/or monetary burden in preparing reports using the taxonomy and would therefore appreciate a simple reporting structure. Consumers or regulators may wish for more information, thus suggesting a more advanced reporting structure. These opinions come into direct conflict. A balance must be achieved between the interests of preparers and consumers while still meeting all functional requirements and regulations (Figure 4-1).</div>
<div class="tdh_066">To resolve these sorts of situations, requirements can be weighted by their importance, such as items that &#8220;make or break&#8221; the project versus items that would be &#8220;nice to have&#8221; or provide moderate benefit. Certain stakeholders may see some goals as highly important while others view them as not necessary or mildly interesting. In addition, each requirement will add a level of preparation and implementation effort, which must also be balanced against the value of the data or system being created.</div>
<div class="tdh_066">It is the job of the taxonomy developers to take into account all functional and non-functional requirements during the design process and determine which are essential or important to the taxonomy&#8217;s success, which can be completed to bolster or facilitate ease of use or particular interests, and which are not relevant or achievable. In the example above, the burden to the preparers may be balanced by the needs of the consumers/regulators in such a way that the taxonomy allows for a minimal time and learning investment on the part of preparers as they create reports while addressing all of the points the regulators and consumers require. Cost-benefit analyses, both in terms of report preparation costs and in development costs for the taxonomy itself, can aid in these decisions. By flagging the most important requirements and/or ranking the requirements to determine their priority, a complex development process can be better organized, and the critical requirements can receive the most attention. It can also help project managers and developers allot the appropriate personnel, effort, and emphasis to each requirement while guiding task list creation and oversight. Developers should also consider the pitfalls of &#8220;creeping elegance,&#8221; where simple solutions become increasingly overcomplicated to achieve functionality that is &#8220;nice to have,&#8221; neat, or elegant but not strictly necessary. In these cases, the cost and complexity quickly outweigh the gains from the solution.</div>
<div class="tdh_066">As a rule, developers should always bear in mind that a taxonomy cannot be &#8220;all things to all people,&#8221; meaning it cannot achieve all use cases or requests/recommendations equally or at all. The most important requirements should take precedence.</div>
<p><!-- Field: Page; Sequence: 68 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->63<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_027"><a name="a_Toc24107549"></a><a name="a_Toc23337695"></a>4.7   Measuring Success</div>
<div class="tdh_066">Once the taxonomy has been developed, the focus then turns to testing and validation. How can the developers know the taxonomy is working as anticipated? What models and methods will be useful in testing the taxonomy? How can interested parties (consumers, regulators, auditors, and other relevant individuals) be certain that the data is correct and valid?</div>
<div class="tdh_066">Depending on the scope of the taxonomy, measuring how successful the transport model is can be a rather complex process. In addition, &#8220;success&#8221; to some stakeholders may not equate &#8220;success&#8221; to others. For example, one consumer may only be concerned with the numeric facts that are part of a calculation, so a calculation arc using those facts that represents an accurate summation may not matter. Another consumer may only be interested in the result of the calculation, so in this case the calculation definition is vital. Testing the taxonomy must address both of these instances. As with defining and ranking requirements and exploring use cases, determining what the measures of success are and how they will be assessed prior to development may be helpful.</div>
<div class="tdh_066">In the end, validating a taxonomy may prove to be almost as important as designing it. There are multiple approaches to error-checking a taxonomy, such as establishing a data quality governance committee that can design data quality rules and ensure proper representation of information. As stated previously, XBRL has some provisions to ensure data integrity, such as concept data types and calculations, definitions, and other relationships that XBRL software can use to check for errors. As a side note, XBRL US Data Quality Committee rules are freely available and can be used to check the consistency and accuracy of XBRL-formatted information.</div>
<div class="tdh_066">Beyond data quality, there is also the issue of determining if the taxonomy is truly meeting its functional requirements and goals. Is the transport model delivering enough of the right kinds of data for consumers to make use of it? Again, this returns to identifying and understanding the requirements and use cases; this will help generate end points in the development process and dictate measures of success. For large scale taxonomies with many use cases, stakeholders, and a large variety of people using the taxonomy, involving more users through public comment and review of candidate schemas, information models, and documentation can be extremely useful. Initial development stages may have only involved the perspectives and opinions of a few key stakeholders, so a public review can open the door to additional insights. Developers can also create sample instance documents using the taxonomy as a means to test and measure the overall success of the taxonomy. Creating samples will highlight areas where concepts are missing or where the structure of the taxonomy may be cumbersome for preparation purposes. These validated and refined sample instances can be disseminated to software providers to see how they will need to adapt to the taxonomy, which can in turn provide feedback on how the taxonomy works with the data itself. These review cycles help guide developers in determining the measures of success and how to properly examine them to be sure the taxonomy is functioning exactly as it should.</div>
<p><!-- Field: Page; Sequence: 69 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->64<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt; float: right; margin: 8px; border: 1px solid #e2e2e2; border-bottom: none;"><a href="#toc">Table of Contents</a></div>
<div class="tdh_028"><a name="a_Toc24107550"></a><a name="a_Toc23337696"></a><a name="a_Ref17796171"></a><a name="a_Ref17796135"></a><a name="a_Ref13047548"></a>5   Building a Transport Data Model</div>
<div class="tdh_027"><a name="c5_transport_data_model"></a><a name="a_Toc24107551"></a><a name="a_Toc23337697"></a>5.1   Getting Started</div>
<div class="tdh_066">Before a taxonomy can be constructed, developers need to create the transport data model. As one can imagine from the previous chapters, this transport model, depending on the use cases and requirements of the project, can be simple or complex. The model itself heavily impacts design choices and the taxonomy development, as well as the eventual ease of use for preparers and consumers. Of course, of paramount importance is the quality of the data that is to be transported and disclosed, and the data model must be sufficiently robust and well-designed to maintain data integrity as well as promote data validation.</div>
<div class="tdh_066">When defining the model, developers must first understand their <i>minimum data set</i>, that is, the amount of data necessary to meet all the use cases, requirements, and regulations involved without including redundant or extraneous information. Defining this data set will guide development. After this crucial step, other topics can be considered, such as extensibility, the XBRL instance document format, and including information from other taxonomies. This chapter provides a guide for defining the data set, building the transport model, making solid design choices, and then designing the taxonomy itself.</div>
<div class="tdh_066">For this chapter, the widget sales example from Chapter 3 will be used to demonstrate the taxonomy design choices. Some changes are made to the example to show differing taxonomy structures. While the discussion in Chapter 3 broadly explored data model types and analogous XBRL constructs, this chapter features a more focused discussion based on modeling a single data set from the initial stages to a completed transport data model.</div>
<div class="tdh_027"><a name="a_Toc24107552"></a><a name="a_Toc23337698"></a>5.2   Developing a Model</div>
<div class="tdh_066">Once the development team has determined the project parameters as outlined in Chapter 4, work can begin on defining the transport model. With the goals in mind, developers must translate the data sets that are currently in one or more originating business models to the XBRL taxonomy. To do so, they must first describe those originating data sets, their dimensionality, and what portions of them will be included in the taxonomy.</div>
<div class="tdh_066">Consider the widget example. This is a sample data set that the developed transport model must represent (Table 5-1 and Table 5-2).</div>
<p class="tdh_046"><img class="tdh_111" src="http://files.xbrl.us/images/tdh/tdh_p1_table_51.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref20994550"></a>Table 5-1. Example widget sales report for Widgets, Inc.</p>  

<p class="tdh_046"><img class="tdh_108" src="http://files.xbrl.us/images/tdh/tdh_p1_table_52.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref20995517"></a>Table 5-2. Example widget production report for Widgets, Inc.</p>  

<p><!-- Field: Page; Sequence: 70 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->65<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Realistically, a taxonomy will contain multiple reports and far more data, and the interactions between the different presentations and tables within the taxonomy may be complex. This simpler example will explore some of these interactions as the chapter progresses.</div>
<p class="tdh_020"><a name="a_Ref22041668"></a><span class="tdh_024">5.2.1     </span>Functional and Non-functional Requirements of the Taxonomy</p>  

<div class="tdh_066">At this juncture, developers should have both the functional and non-functional requirements of the data model outlined (Section 4.1). With these requirements in mind, developers can begin to map the requirements onto the data. If data sets already exist from current or legacy systems, developers should examine how the requirements align with the structure of these data sets. Otherwise, developers can begin to design new data sets.</div>
<div class="tdh_066">In the widget example, the goal is to determine the revenue of each individual widget type. Therefore, the taxonomy may be modeled by separating costs of widget production versus widget sales. This is the functional requirement and would involve reporting total purchases of widgets and total cost to produce widgets. The available data, as defined in Table 5-1 and Table 5-2, includes components of these values but not the values themselves, though those values can be derived.</div>
<div class="tdh_066">Suppose, though, that there are non-functional requirements. These could include reporting more specific information, including reporting individual sales of widgets. Perhaps a particular use case requires this information or reports currently contain this information and changing this would affect workflow. This is a non-functional requirement because this information is <i>not needed </i>to determine revenue by widget type. The widget example will assume that information about individual widget sales is a non-functional requirement and will be included in the modeling process.</div>
<p class="tdh_020"><span class="tdh_024">5.2.2     </span>Determining the Minimum Data Set</p>  

<div class="tdh_066">As an initial step, the developer must determine what constitutes a complete data set for an instance. This <i>minimum data set</i> should be free of redundant or extraneous information while representing all the necessary data. A parsimonious data model will lend itself to a well-structured, easily understandable, and logically organized taxonomy.</div>
<div class="tdh_066">Depending on the breadth and scope of the taxonomy being developed, the minimum data set may not be a single data set but multiple data sets from multiple sources. For example, a taxonomy for manufacturing reporting may include numerous tables of related but semantically independent information (such as a table of inventory of raw materials for a set of products and a table of manufacturing costs associated with the same products). Each one of those may become part of the minimum data set. These multiple data sets can be derived from multiple sources, such as paper forms or pre-existing software databases.</div>
<div class="tdh_066">For the widget example, the minimum data set aligns directly with the reporting requirements. Preparers must report widget unit sales by type, price, and customer, total widget purchases in US dollars, and the date of each purchase. In addition, they must report the total cost to produce each widget type. Finally, they must report the total revenue by widget type. Preparers must also report the period for which the data pertains and the reporting company name. This thus forms the minimum data set for this simple taxonomy.</div>
<p class="tdh_026">5.2.2.1     Current and Legacy Systems</p>  

<div class="tdh_066">Current and legacy systems can provide a good basis for determining the minimum data set. While current systems are a good starting point for determining the minimum data set, developers should consider whether these requirements are still appropriate. Often when reporting requirements evolve over years or even decades, suboptimal data collection systems are adapted through &#8220;work-arounds&#8221; to avoid completely re-engineering the system. These work-arounds may &#8220;do the job&#8221; but may not be ideal, and a move to XBRL provides a good time to revisit these issues.</div>
<div class="tdh_066">The types of systems or data formats that may help describe the originating data set may be:</div>
<ul>
<li><span class="tdh_190">paper/PDF forms</span></li>
<li><span class="tdh_190">spreadsheets or CSV files</span></li>
</ul>
<p><!-- Field: Page; Sequence: 71 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->66<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<ul>
<li><span class="tdh_190">other XML forms</span></li>
<li><span class="tdh_190">databases</span></li>
<li><span class="tdh_190">websites</span></li>
</ul>
<div class="tdh_066">Each of these systems has a format and structure inherent to it. It is the job of the developer to determine how those formats and systems &#8220;fit in&#8221; with the taxonomy. As said previously, developers should gather these systems and identify the necessary data while removing the redundant or irrelevant information to create a parsimonious, minimum data set upon which the taxonomy can be built.</div>
<p class="tdh_020"><span class="tdh_024">5.2.3     </span>Creating a Conceptual Data Model</p>  

<div class="tdh_066">With the minimum data set and the requirements clearly defined, the task becomes actually realizing those requirements through the taxonomy itself, i.e., defining a <i>conceptual data model</i>. This is the initial modeling of the taxonomy, focusing on static, overarching requirements and use cases and how the minimum data set fulfills them.</div>
<div class="tdh_066">This step leads into an important part of defining the data model: developers should strive to reduce repetitive information, removing all of it if possible. If, as mentioned above, the data underlying multiple forms is being united in an XBRL taxonomy, there may be duplicative information (such as company name, for example, or widget type in the widget example). Likewise, developers should identify information that is the same in multiple data sets even if it is the focus in one data set and only contextual in another. Accounting for these situations during the design process can reduce the creation of redundant concepts and improper dimensionality. Additionally, there may be concepts that appear to be the same in multiple data sets but in reality are not, and these must be identified, separated, and unambiguously defined in the taxonomy.</div>
<p class="tdh_020"><span class="tdh_024">5.2.4     </span>Data Architecture</p>  

<div class="tdh_066"><a name="c5_relational_data"></a>Once the requirements are defined in the conceptual data model, developers can begin to develop a <i>logical data model</i>, which explores the data points in the conceptual data model and, importantly, how they relate to each other and other data constructs. Because the widget example does not contain many complex data relationships, the logical data model is very similar to the conceptual data model. The goal is to report widget revenue by type, which is a derived value comprised of widget sales and widget production costs. Widget sales and production costs are in the data set supplied, but the revenue is not. If the goal is to report value X, but X is comprised of data points A, B, C (all with different contextual information), knowledge of A, B, C is required if X is not part of the current data set (as in the widget example). This is not necessarily always the case. The data architecture should be able to represent the entire minimum data set, including any required derived values as set forth by the fundamental requirements. In all cases, the conceptual data model should drive the logical data model.</div>
<div class="tdh_066">Again, the minimum data set, and therefore the conceptual and logical data models, should be parsimonious. Avoid unnecessary information or redundant data.</div>
<p class="tdh_026">5.2.4.1     Standard Data Relationships</p>  

<div class="tdh_066">Chapter 3 briefly introduced a few standard data relationships common to a relational data model. The <i>one-to-one</i> relationship exists or can exist between one data point and another data point. These are very common in many reporting environments. The <i>one-to-many</i> relationship exists or can exist between one data point and many other data points. For example, the total revenue of widget sales data point is comprised of one or more individual sales of widget types; therefore, there is a one-to-many relationship between the total sales and the sales of individual types. A <i>many-to-many</i> relationship defines a relationship that exists or can exist among many data points. If the fundamental requirement is to report <i>all </i>widget sales, this situation can produce many-to-many relationships as seen in Section 3.2.3.</div>
<div class="tdh_066">There can also be <i>zero-to-one</i> relationships, where one data point of a pair can exist with or without the other data point. This concept extends to <i>zero-to-many</i> relationships. These relationships are more commonly seen as the construct: if data point X exists, data point Y may or may not exist. This is not to be confused with exclusion relationships, such as if data point X exists, data point Y cannot exist.</div>
<p><!-- Field: Page; Sequence: 72 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->67<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Developers should examine the minimum data set and map out these relationships among their data points as they develop their logical data model. Any modeling methodology may be employed so long as it is appropriate to the data, but the methodology should be used consistently to create coherent models.</div>
<div class="tdh_066">To begin defining data relationships, developers should first determine the primary data point or points necessary to realize the requirements. In the widget example, this would be total sales and total expenses per widget type. This means that the widget type semantic identifier will define the data relationships. Building on this, additional relationships can be determined. Total sales and total expenses are comprised of one or more individual sales and expenses, respectively. These are one-to-many relationships. There are one-to-one relationships for each component of the sales and expenses. An individual sale has only one widget type, one client, one date, etc., and each individual expense is comprised of one widget type, quantity, and price per widget.</div>
<div class="tdh_066">Note that because the fundamental requirements stipulate that only sales by widget type be reported, sales that include more than one widget type must be separated by type to fit the data model. This may not align with how sales data is typically recorded in the industry (if it is tracked by client and date or an invoice number, for example). Developers should decide whether this design choice is a burden on preparers or if the data model should be adjusted. For this example, the data model will not be adjusted to account for this.</div>
<div class="tdh_066">This draft of a possible logical data model for the widget taxonomy appears in Figure 5-1.</div>
<p class="tdh_099"><img class="tdh_160" src="http://files.xbrl.us/images/tdh/tdh_p1_036.jpg" alt="A screenshot of a cell phone Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref21093191"></a>Figure 5-1. A possible initial logical data model for the widget taxonomy</p>  

<div class="tdh_066">The items in orange are the same for each section of the model. The meaning of Widget Type does not change despite its context. However, Quantity does gain different meaning depending on its context (for example, sale versus expense). One could consider Widget Type to be a key for the tables that not only logically links the components of the data model together but also confers uniqueness to the data point. More is discussed about uniqueness in the next section.</div>
<div class="tdh_066">The items in blue are also the same, but they pertain to the individual report <i>not </i>the logical data model. While it is important to account for this information in the planning process, these data points do not belong in the XBRL taxonomy but are rather defined in an XBRL report. Because they are constant within the report, there is no need for contextual knowledge of this information.</div>
<p><!-- Field: Page; Sequence: 73 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->68<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_026">5.2.4.2     Defining Uniqueness</p>  

<div class="tdh_066">As developers map and define data relationships, uniqueness should become apparent through those relationships. The same data point may appear in multiple places within the logical data model, but each appearance should either be unique through its context (relationships with other data points) <i>or </i>be the exact same data point (interpreted the same way). This is an important step in creating the model. If developers find they cannot represent necessary uniqueness with the relationships they have designed, more information (and therefore more contextual information) may be necessary.</div>
<div class="tdh_066">In the widget logical data model, the Widget Type defines data that is unique through its context, whereas the Company and Report Date are examples of data points that are exactly the same. It should be noted that in the current data model, if two individual sales are made by the same client on the same day of the same amounts of the same widget type, the data will <i>not</i> be unique. In this case, the sales either must be summed by the preparer or an additional arbitrary dimension must be added to maintain uniqueness. This could be an invoice or order number. See Section 3.3.1.2 for more information.</div>
<div class="tdh_027"><a name="a_Toc24107553"></a><a name="a_Toc23337699"></a>5.3   Transforming a Data Model to a Transport Model</div>
<div class="tdh_066">With a logical data model defined, developers can create a <i>physical data model</i>, which represents that model as it will appear in XBRL format. The physical data model should indicate a) all the concepts of the taxonomy, including their properties, and b) the relationships among the concepts (as arcs or through an abstract hierarchical structure, for example). This physical model then becomes the transport model.</div>
<p class="tdh_020"><span class="tdh_024">5.3.1     </span>Data Types</p>  

<div class="tdh_066">Each data point in the logical data model should be examined and labeled with its corresponding data type. As a general rule of thumb, the most restrictive datatype should be used where possible. For example, a numeric value should have a numeric data type that allows for the mathematical precision that the data requires. If the data point contains a monetary amount that will never be more precise than two decimal places, a data type can be chosen or created that enforces this constraint. Developers should also bear in mind the relationships among the data points may influence the constraints of the data type. For example, a data point that normally represents only positive values may become negative in a specific context within the data model, such as an adjustments context. Inventory lost would normally be a positive value, except in the event where inventory may be found or restored. In this case, it would become negative.</div>
<div class="tdh_066">All datatypes must be drawn from the XBRL standard datatypes (see Section 2.3.1 and Appendix A). If there is no standard datatype that can accurately represent a data point, developers may create a custom datatype.</div>
<div class="tdh_066">For a discussion of the possible data types for the widget taxonomy and the reasons behind their selection, see 3.4.1.1.</div>
<p class="tdh_020"><span class="tdh_024">5.3.2     </span>Creating XBRL Dimensions</p>  

<div class="tdh_066"><a name="c5_xbrl_dimension"></a>Each data point in the logical data model must be represented by one concept core dimension and other taxonomy-defined or core dimensions. The concept core dimension should pertain to the semantic meaning of that data point. Given the relationship of that data point to other data points, different sets of taxonomy-defined dimensions may be used with the concept core dimension. For example, one table may contain data for sales by region and another may contain data for sales by product type, but the concept core dimension for both tables is sales and therefore must contain the same value for the total. By using the same concept core dimension, this relationship between the totals is enforced. The set of other XBRL dimensions differ, which also confers uniqueness.</div>
<div class="tdh_066">Only concept core and taxonomy-defined dimensions are part of the XBRL taxonomy; other core dimensions are defined in the instance document by the preparer. This is because the semantic meaning of these core dimensions is static and defined in the <a href="https://specifications.xbrl.org/work-product-index-group-base-spec-base-spec.html"><span class="tdh_035"><i><u>XBRL Specification</u></i></span></a>; only the values changes from report to report. Taxonomy-defined dimensions and concept core dimensions should not be created for the contextual information the other core XBRL dimensions represent, such as units or reporting period.</div>
<p><!-- Field: Page; Sequence: 74 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->69<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Refer to Figure 2-17 for more information on what definitions are contained in the taxonomy versus the instance document.</div>
<div class="tdh_066">Note that data points may have the same natural language name (such as &#8220;cost&#8221; or &#8220;quantity&#8221;) but semantically or contextually mean different things. Developers should strive to identify these situations and ensure concept names are unique and unambiguous.</div>
<div class="tdh_066">As concepts are defined, developers should also define their properties, labels, documentation, and relevant references. This begins to build the library of information that will become the transport model. The logical data model for the widget taxonomy, with its concept names and data types defined, now appears as:</div>
<p class="tdh_099"><img class="tdh_162" src="http://files.xbrl.us/images/tdh/tdh_p1_037.jpg" alt="A screenshot of a cell phone Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref23242770"></a>Figure 5-2. A more refined logical data model for the widget taxonomy with concept names and data types</p>  

<div class="tdh_066">The transport model in Figure 5-2 is not yet complete because the relationships among the concepts have not been modeled. To do this, taxonomy-defined dimensions must be created.</div>
<p class="tdh_026">5.3.2.1     Defining the Concept Core Dimensions</p>  

<div class="tdh_066">This is a crucial step in designing the taxonomy transport model. The concept core dimensions directly relate to the data that must be reported as per the fundamental requirements. Therefore, these should be defined first, with all other contextual information becoming taxonomy-defined dimensions.</div>
<div class="tdh_066">In general, understanding data becomes more complicated with increasing contextual information. Therefore, it is often desirable to represent as much relevant information as possible with concept core dimensions. In Section 3.3.1.2, there is a discussion about the implications of representing data with concept core versus taxonomy-defined dimensions. In the widget taxonomy, the requirements dictate only that the widgets sold and widget expenses be represented by concept core dimensions; these are the key reporting values. However, more information lends itself to concept core dimension representation to make the model more simplified and easier to understand.</div>
<p><!-- Field: Page; Sequence: 75 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->70<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">The data model for sales in the widget taxonomy could have the following design progression:</div>
<table class="tdh_239" cellspacing="0" cellpadding="0">
<tbody>
<tr>
<td class="tdh_219" colspan="2"><b>Initial Design</b></td>
<td class="tdh_218" colspan="2"><b>Adding Uniqueness</b></td>
<td class="tdh_218" colspan="2"><b>Final Model</b></td>
</tr>
<tr class="tdh_205">
<td class="tdh_005"><b>CustomerName</b></td>
<td class="tdh_006">TDD</td>
<td class="tdh_006">CustomerName</td>
<td class="tdh_006">CCD</td>
<td class="tdh_006">CustomerName</td>
<td class="tdh_006">CCD</td>
</tr>
<tr>
<td class="tdh_222"><b>OrderDate</b></td>
<td class="tdh_230">TDD</td>
<td class="tdh_224">OrderDate</td>
<td class="tdh_228">CCD</td>
<td class="tdh_226">OrderDate</td>
<td class="tdh_228">CCD</td>
</tr>
<tr class="tdh_205">
<td class="tdh_005"><b>PricePerWidget</b></td>
<td class="tdh_006">TDD</td>
<td class="tdh_006">PricePerWidget</td>
<td class="tdh_006">CCD</td>
<td class="tdh_006">PricePerWidget</td>
<td class="tdh_006">CCD</td>
</tr>
<tr>
<td class="tdh_213"><b>WidgetSaleIncome</b></td>
<td class="tdh_215">CCD</td>
<td class="tdh_215">WidgetSaleIncome</td>
<td class="tdh_215">CCD</td>
<td class="tdh_215">WidgetSaleIncome</td>
<td class="tdh_215">CCD</td>
</tr>
<tr class="tdh_205">
<td class="tdh_005"><b>WidgetType</b></td>
<td class="tdh_006">TDD</td>
<td class="tdh_006">WidgetType</td>
<td class="tdh_006">CCD</td>
<td class="tdh_006">WidgetType</td>
<td class="tdh_006">TDD</td>
</tr>
<tr>
<td class="tdh_213"><b>WidgetsSold</b></td>
<td class="tdh_215">TDD</td>
<td class="tdh_215">WidgetsSold</td>
<td class="tdh_215">CCD</td>
<td class="tdh_215">WidgetsSold</td>
<td class="tdh_215">CCD</td>
</tr>
<tr class="tdh_205">
<td class="tdh_005"></td>
<td class="tdh_006"></td>
<td class="tdh_006">Invoice</td>
<td class="tdh_006">TDD</td>
<td class="tdh_006">Invoice</td>
<td class="tdh_006">TDD</td>
</tr>
<tr>
<td class="tdh_214" colspan="6">
<p class="tdh_097"><b>CCD = Concept Core Dimension</b></p>  

<p class="tdh_097"><b>TDD = Taxonomy-defined Dimension</b></p>  

</td>
</tr>
</tbody>
</table>
<p class="tdh_106"><a name="a_Ref21427078"></a>Table 5-3. The widget taxonomy design process for the individual widget sales table</p>  

<div class="tdh_066">In Table 5-3, the design process can begin with an initial minimum data set, wherein, by the requirements, only the WidgetSaleIncome concept is a concept core dimension. All other concepts are taxonomy-defined dimensions, which adds contextual data and uniqueness to each data point. This model is quite complex for such simple data when organized this way; a single data point is reported using five taxonomy-defined dimensions to ensure that the value is unique and unambiguously understood. Uniqueness can be gained through adding an arbitrary XBRL dimension, in this case Invoice. Adding this dimension significantly reduces the complexity of the model as seen in the second column. This is because Invoice is the only contextual information necessary to create unique data (as each sale should have its own invoice number). This allows the other concepts to become concept core dimensions.</div>
<div class="tdh_066">However, the requirement of the taxonomy is to compare widget sales by widget type. Therefore, widget type should be contextual and this is represented in the final column by returning it to a taxonomy-defined dimension. This choice is strictly based on the requirements of the taxonomy. If the goal is to compare sales by customer, CustomerName would become a taxonomy-defined dimension. Developers should adjust the model to meet the requirements as succinctly and clearly as possible.</div>
<div class="tdh_066">It is also possible to model WidgetType as both a concept core dimension and a taxonomy-defined dimension, which lets the preparers decide how to implement this dimension. As is often the case, this provides greater flexibility but reduces comparability. This approach is advantageous for optional information.</div>
<div class="tdh_066">This process of differentiating between concept core and taxonomy-defined XBRL dimensions should be completed for every table or other relevant data set coming into the taxonomy. The same dimensions can, and potentially should, appear on multiple tables if their semantic meaning is constant. It is also possible for a concept core dimension to become a taxonomy-defined dimension between different tables and vice versa depending on the needs of the data model. If this is the case, developers should advise preparers on which concepts apply to which tables.</div>
<p class="tdh_026"><a name="a_Ref20226696"></a>5.3.2.2     Whether to Use Explicit or Typed Taxonomy-defined Dimensions</p>  

<div class="tdh_066">Once developers have identified the taxonomy-defined dimensions in the data model, they must decide whether those dimensions will be typed or explicit. Section 3.4.2 briefly discussed the difference between explicit and typed taxonomy-defined dimensions. Depending on the nature of the relationships and the need for extensibility, developers must decide which kind of taxonomy-defined dimension to use. Regardless of the type of the relationship (one-to-many or many-to-many, for example), either of these kinds of dimensions can apply. The domain of data to be represented should dictate the choice.</div>
<p class="tdh_032">5.3.2.2.1     Explicit Taxonomy-defined Dimensions</p>  

<div class="tdh_066">Explicit taxonomy-defined dimensions allow the preparer to specify the domain and values for that domain. They can also be used when the XBRL dimension allows for concepts that may be hierarchical in</div>
<p><!-- Field: Page; Sequence: 76 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->71<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">nature. This is the only method of expressing taxonomy-defined dimensions that supports a hierarchical domain. They do not have to be used solely for this purpose; they can also represent flat relationships.</div>
<div class="tdh_066">As an example, a taxonomy-defined dimension to represent widget types could be implemented as an explicit taxonomy-defined dimension. If there is a set number of widget types (Circular, Rectangular, Triangular), the domain would include all these widget types and only these types. If developers allow extensibility, preparers could add their own member items to represent custom widget types and include them within this domain. Additionally, with extensibility preparers could narrow the domain of this axis. If a company produces only variations of circular widgets, the preparer of this report could create a domain XBRL dimension explicitly for circular widgets and member concepts for the specific circular types. Because the preparer would define the relationships among these concepts and this taxonomy-defined dimension, comparability is still maintained with the addition of their specific information. For more information on extensibility, see Section 5.4.2.</div>
<p class="tdh_032">5.3.2.2.2     Typed Taxonomy-defined Dimensions</p>  

<div class="tdh_066">A typed taxonomy-defined dimension limits the domain of potential values to the specified data type. Depending on the data type, this can be very broad or extremely narrow. Importantly, it limits extensibility because no values outside of that data type can be part of the domain. Additionally, there are no methods of representing hierarchical relationships among members.</div>
<div class="tdh_066">As an example, if the widget type taxonomy-defined dimension is implemented as a typed dimension with a string data type, preparers could enter almost any information as widget types. Note that this may greatly reduce comparability, but it increases preparer flexibility without needing extensibility. However, if the data type is limited to an enumeration of string types, preparers would have no choices but those set forth by the developers in that list.</div>
<p class="tdh_032">5.3.2.2.3     Choosing the Best Kind of Taxonomy-defined Dimension</p>  

<div class="tdh_066">The nature of the data and the reporting requirements should help dictate how to select the appropriate kind of taxonomy-defined dimension. In general, typed taxonomy-defined dimensions should be employed when the domain of the axis is fixed or when the individual values of the axis are not relevant to the data model. For example, in the widget taxonomy sales table, the invoice dimension has values that are not necessarily relevant to the data model or the fundamental requirements of the taxonomy but rather maintain uniqueness among the facts. Therefore, this dimension is best suited as a typed taxonomy-defined dimension, potentially with an integer or string data type depending on how the order identifier is represented.</div>
<div class="tdh_066">Conversely, widget type can be handled as either an explicit or typed taxonomy-defined dimension. The sections above explore the ramifications of both decisions. In the widget taxonomy, WidgetType will be treated as an explicit taxonomy-defined dimension.</div>
<p class="tdh_026">5.3.2.3     Completing the Data Model</p>  

<div class="tdh_066">At this stage, developers can begin to collect their library of concepts. In addition, some concept properties, such as their names, data types, and labels, can begin to be defined. Any relevant regulatory governance can be defined as well. Alongside this process, developers may choose to begin documenting their taxonomy. Note that the library of concepts may not be complete at this time as abstract concepts necessary to represent additional relationships may be required.</div>
<div class="tdh_066">This is also an ideal moment, with most of the physical data model developed, to double-check that the original requirements of the taxonomy are still being implemented and that all the data included in the model is necessary or otherwise relevant.</div>
<p><!-- Field: Page; Sequence: 77 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->72<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Returning to the widget taxonomy, the requirements outlined in this chapter do not actually require the break-down of the expenses by widget type to be reported (Section 5.2.1). The number of widgets produced and the production cost per widget are not necessary to meet the functional requirements. Therefore, there is no need to track this information within the taxonomy. The final model may appear like this (Figure 5-3):</div>
<p class="tdh_099"><img class="tdh_161" src="http://files.xbrl.us/images/tdh/tdh_p1_038.jpg" alt="A screenshot of a cell phone Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref21432910"></a><a name="a_Ref23243345"></a>Figure 5-3. The final physical data model for the widget taxonomy</p>  

<div class="tdh_066">The taxonomy-defined dimensions appear in orange text. The concept core dimensions are beneath them in black text. The information that is included only in the XBRL report (the reporting company and report date) have been removed. Note that a fourth table has been added for widget performance. This is a derived value and representative of the taxonomy&#8217;s functional requirement: reporting how each widget performs as a function of sales and production costs. Adding this table ensures that the taxonomy meets its goals.</div>
<div class="tdh_066">Because the requirements and minimum data set allowed for the removal of CostsPerWidget and WidgetsProduced and for ProductionExpense to be incorporated into WidgetExpenses, Table 5-2 cannot be produced from this data model. Since this was not part of the requirements, it is not a concern. It is possible in this case to drop this information from the conceptual and logical data models and therefore not model these data points at all. In simple taxonomies where the relationships are more obvious, this can be an easier approach.</div>
<p class="tdh_020"><a name="a_Ref21685655"></a><span class="tdh_024">5.3.3     </span>Represented Relationships</p>  

<div class="tdh_066">XBRL linkbase documents define the relationships among the concepts. These relationships have been discussed throughout this handbook, but they most often include presentations, calculations, and definitions. The relationships among the data points, and therefore the concepts related to those data points, should become clear from the physical data model (Figure 5-3.).</div>
<div class="tdh_066">The relationships within the logical data model become linkbase documents for the taxonomy. Every concept core and taxonomy-defined dimension should appear in these relationships, unless upon subsequent releases of the taxonomy, the dimension has been deprecated. In addition to presentations, developers should define calculations and definitions where possible to assist in both interpretation and validation of the data. Finally, developers could use linkbase documents to indicate to preparers what</div>
<p><!-- Field: Page; Sequence: 78 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->73<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">information is required for the minimum data set if more concepts are available than what is necessary to prepare a particular type of report.</div>
<div class="tdh_066">The widget example lends itself to two presentations: individual widget sales by widget type, and widget performance by type. There could be up to four presentations, but including these additional presentations adds little unique or relevant information. The widget performance presentation would include both the total sales table and the total expenses table. In addition, the revenue by widget type concept can be derived by a calculation between the WidgetSales and WidgetExpenses concepts for each widget type. This represents an <i>imputed value</i>.</div>
<div class="tdh_066">WidgetSales, however, cannot be derived through a calculation with the way the model is currently structured. This is because calculations cannot bridge between axes, and WidgetSales is the summation of all WidgetSaleIncome concepts across the Invoice axis.</div>
<div class="tdh_066">The definition and presentation linkbases are very similar for this taxonomy. In addition, developers should consider other pertinent linkbases, such as labels and references. These are not relevant from a data modeling standpoint and are discussed in Chapter 6.</div>
<p class="tdh_020"><span class="tdh_024">5.3.4     </span>Intrinsic Relationships</p>  

<div class="tdh_066">In addition to directly defined relationships, logical data models often contain intrinsic and other logical relationships that XBRL may not directly represent. Intrinsic relationships include data points that must have the same value, data points that require the presence of other data points, and data points that cannot exist with another data point defined. These relationships may depend heavily upon the nature of information the model represents. If there is no way to easily represent this information in the transport data model through a definition or other concept arc, developers may want to consider adding data validation rules to ensure these intrinsic relationships are upheld.</div>
<div class="tdh_066">In the previous section, there was no way to ensure WidgetSales is the summation of all WidgetSaleIncome concepts across all Invoice axes. This cannot be accomplished with an XBRL calculation. However, this relationship can be achieved with an intrinsic relationship. To do so, there are multiple options. The first would be adding validation as mentioned above. This is outside the scope of the taxonomy itself but rather pertains to data quality rules. The second option involves restructuring the data model slightly. WidgetSaleIncome and WidgetSales could be represented as a single concept core dimension and thus become one XBRL fact. When the concept core dimension does not intersect with an Invoice taxonomy-defined dimension (such as in the Total Sales table), the value of this fact is representative of the domain of the Invoice taxonomy-defined dimension (i.e., a summation of all purchases). This would be represented with definition relationships. As a side-effect, the purchase total will appear not only on the total sales table but also on the individual sales table, even though the value is only reported once. Note XBRL enforces that the values are the same in both tables because they become the same fact, not necessarily that the summation of each individual widget purchase truly equals the total purchase.</div>
<div class="tdh_066">The discussion of creating the widget taxonomy continues in Chapter 6. The following sections discuss other important aspects of taxonomy development unrelated to the data model.</div>
<div class="tdh_027"><a name="a_Toc24107554"></a><a name="a_Toc23337700"></a>5.4   Development Choices</div>
<div class="tdh_066">Once the transport model has been defined, developers should consider additional development choices. These considerations are outlined below.</div>
<p class="tdh_020"><a name="a_Ref19879567"></a><span class="tdh_024">5.4.1     </span>Transport Format</p>  

<div class="tdh_066">While the transport format has minor influence on the taxonomy development process, it has major implications both for XBRL report preparers and for data consumers. Note again that the taxonomy schema and linkbase documents themselves must be provided in XML. When extensibility is allowed, additional schema documents and linkbases can be provided by users; otherwise, they may be referenced from a common location. Transport formats have been briefly discussed in Chapters 1 and 2 and are discussed below in greater detail. Developers can allow multiple transport formats or choose not</div>
<p><!-- Field: Page; Sequence: 79 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->74<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">to specify a format at all. The choice is dependent upon the goals of the taxonomy, the information supply chain itself, and the needs of the industry. Regardless of the decision itself, guidance should be provided to taxonomy users about the transport format(s) selected and how they may be used to create XBRL report (see Chapter 7 for more information on documenting the transport format).</div>
<p class="tdh_026">5.4.1.1     XBRL as XML</p>  

<div class="tdh_066">Instance data can be stored in XML format (dictated by the <a href="https://specifications.xbrl.org/work-product-index-group-base-spec-base-spec.html"><span class="tdh_035"><i><u>XBRL Specification</u></i></span></a>), which is the traditional transport format for XBRL data. XML &#8220;tags&#8221; the data with elements defined in one or more schema, which can express a wide range of data types. An advantage of using XML as a transport format is that developers do not need to deal with multiple file types and formats, as all documents and supporting linkbases are in XML. Additionally, any XML validator can validate the syntax of the file as well as basic datatypes. Finally, XBRL that is based on XML can better handle mixed content (such as including JSON or CSV formatted facts or binary data), as is commonly found in business and financial reporting.</div>
<div class="tdh_066">The default encoding for XML is UTF-8, although some systems only accept ASCII using character entities for special characters. A recommendation for XBRL-XML mapping is available with the <a href="https://specifications.xbrl.org/work-product-index-open-information-model-open-information-model.html"><span class="tdh_035"><i><u>XBRL Open Information Model</u></i></span></a>.</div>
<p class="tdh_026">5.4.1.2     Inline XBRL</p>  

<div class="tdh_066">Inline XBRL (iXBRL) allows the instance data to be embedded in an XHTML document. This is iXBRL&#8217;s principal advantage, that machine readable data is located right within the human readable report. Another advantage is that when users edit the HTML document, they are editing the XBRL data at the same time.</div>
<div class="tdh_066">Characters in Inline XBRL can be encoded as legal XML character entities. Depending on the platform used, it may accept either ASCII or UTF-8. The default encoding for XML and XHTML is UTF-8.</div>
<p class="tdh_026">5.4.1.3     JSON</p>  

<div class="tdh_066">JSON, or JavaScript Object Notation, is a text format that provides for the expression of complex structured data. A number of programming languages will natively create and read JSON. XBRL International provides a specification for storing instance information in a JSON report. An advantage of using JSON for the instance document is that many web development languages can easily parse and write JSON natively leading to a fast development cycle of a XBRL enabled webpage.</div>
<div class="tdh_066">Text within JSON objects is usually Unicode encoded as UTF-8. <a name="a_Hlk24718861"></a>A recommendation for XBRL-JSON mapping is available with the <a href="https://specifications.xbrl.org/work-product-index-open-information-model-open-information-model.html"><span class="tdh_035"><i><u>XBRL Open Information Model</u></i></span></a>.</div>
<p class="tdh_026">5.4.1.4     CSV</p>  

<div class="tdh_066">CSV (Comma Separated Values or comma delimited) is another option for transport. XBRL International provides a specification for storing instance information in a CSV report. An advantage of using CSV is it is very easy to parse, read by many computer languages, and is very compact. However, because CSV is a flat structure it is harder to represent many XBRL constructs and is therefore hard to read. CSV can be a good option for reporting information where the data structure is fairly constant and only the fact values change from report to report. In addition, preparers may already be familiar with CSV as it is common in spreadsheet usage.</div>
<div class="tdh_066">Text within CSV has no default character encoding but is generally ASCII or UTF-8. A recommendation for XBRL-CSV mapping is available with the <a href="https://specifications.xbrl.org/work-product-index-open-information-model-open-information-model.html"><span class="tdh_035"><i><u>XBRL Open Information Model</u></i></span></a>.</div>
<p class="tdh_020"><a name="a_Ref21421874"></a><span class="tdh_024">5.4.2     </span>Preparer Extensibility</p>  

<div class="tdh_066"><a name="c5_extensibility"></a>A fundamental design question for any taxonomy is whether it is extensible by the preparers and to what extent. Extensibility has been discussed in Section 3.6, but as a review, developers may choose to allow preparers to extend an open taxonomy by adding custom concepts, datatypes, labels, presentations, calculations, footnotes, and additional taxonomies. Permitting extensibility is a major design choice with numerous implications. While it allows preparers to represent their data perhaps more accurately by</div>
<p><!-- Field: Page; Sequence: 80 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->75<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">permitting them to create their own constructs, this can significantly reduce comparability among XBRL instance documents.</div>
<div class="tdh_066">When deciding to allow extensibility, developers should first consider the reasons why the taxonomy should be open. The reasons will guide determining the methods through which preparers can extend the taxonomy. The following sections work through some scenarios related to extensibility decisions.</div>
<div class="tdh_066">It should be noted that extensibility is not a replacement for updating and maintaining the taxonomy. Developers should also very carefully define the conditions under which extensibility is permitted and what other information should be provided by preparers to support the constructs they change and/or add to the taxonomy.</div>
<p class="tdh_026">5.4.2.1     Allowing Custom Footnotes</p>  

<div class="tdh_066">With this method, preparers can link their own footnote text to facts using the note core ID dimension. Adding footnotes in this way has very little impact on the comparability of the data.</div>
<p class="tdh_072"><i>Impact on Comparability: </i>Low</p>  

<div class="tdh_066"><i>Requires:</i> None</div>
<p class="tdh_026"><a name="a_Ref20992976"></a>5.4.2.2     Allowing Custom Labels</p>  

<div class="tdh_066">Preparers will be permitted to create and use custom labels for the concepts already included in the taxonomy. Again, the impact of this on comparability is very low because this only changes the human readable documentation associated with the concepts.</div>
<p class="tdh_072"><i>Impact on Comparability: </i>Low</p>  

<div class="tdh_066"><i>Requires:</i> None</div>
<p class="tdh_026">5.4.2.3     Allowing Calculations, Definitions, and Presentations</p>  

<div class="tdh_066">In this case, preparers are essentially allowed to rearrange concept relationships to better suit their reporting needs. These concepts already exist in the taxonomy and are not being changed by the extensibility; rather, the change appears in how the concepts relate to one another. Because the concepts themselves remain stable and the taxonomy-defined relationships remain available, the impact on comparability is low.</div>
<p class="tdh_072"><i>Impact on Comparability: </i>Low</p>  

<div class="tdh_066"><i>Requires:</i> None</div>
<p class="tdh_026">5.4.2.4     Allowing Custom Taxonomy-Defined Dimensions</p>  

<div class="tdh_066">If the taxonomy makes use of a dimension with explicit members, it may be reasonable to allow preparers to create their own members for this dimension. For example, if multiple companies need to report their widget production by type, allowing them to create their own taxonomy-defined dimensions for widget types creates enhanced accuracy in the report.</div>
<div class="tdh_066">Depending on the explicit dimension, extensibility may not be necessary at all because the set of allowable values does not change very often from reporter to reporter. For example, if all reporting companies for a taxonomy are located within the United States, there is no reason to permit extensibility for a taxonomy-defined dimension representing a geographic location.</div>
<p class="tdh_072"><i>Impact on Comparability: </i>Medium</p>  

<div class="tdh_066"><i>Requires:</i> Custom labels, definitions, presentations</div>
<p class="tdh_026">5.4.2.5     Allowing Custom Concept Core Dimensions</p>  

<div class="tdh_066">This type of extensibility permits preparers to create their own concept core dimensions which requires preparers to define the properties and labels of those concepts, as well as how the custom concept relates to other concepts within the taxonomy. This sort of extensibility may be appropriate for a very</div>
<p><!-- Field: Page; Sequence: 81 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->76<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">open taxonomy or one in development, where developers may be interested in or relying on preparers to add concepts to more fully flesh out the reporting environment or add depth to the taxonomy.</div>
<p class="tdh_072"><i>Impact on Comparability: </i>High</p>  

<div class="tdh_066"><i>Requires:</i> Custom labels, calculations, definitions, presentations</div>
<p class="tdh_026">5.4.2.6     Allowing Custom Data Types</p>  

<div class="tdh_066">With this type of extensibility, preparers can create their own data types which may be needed to represent newly created custom concepts. This sort of extensibility may be appropriate for a very open taxonomy or one in development, where developers may be interested in or relying on preparers to add concepts to more fully flesh out the reporting environment or add depth to the taxonomy.</div>
<div class="tdh_066">Note that, because the properties of another schema&#8217;s concepts cannot be changed, preparers cannot link custom data types to pre-existing concepts. These can only be applied to custom concepts. This does reduce the impact on comparability to a level similar to using custom concepts.</div>
<p class="tdh_072"><i>Impact on Comparability: </i>High</p>  

<div class="tdh_066"><i>Requires:</i> Custom concept core dimensions</div>
<p class="tdh_026">5.4.2.7     Adding Other Taxonomies</p>  

<div class="tdh_066">With the highest impact on comparability, preparers can be permitted to include other taxonomies in their reports. This opens other taxonomies (their concepts, data types, and concept relationships) for use within a single XBRL report. While this affords preparers great power in that they include additional taxonomies as they see fit or necessary to express their data, it also can drastically reduce comparability. Developers should permit extensible taxonomies with extreme caution.</div>
<div class="tdh_066">If other taxonomies are necessary, developers can include them in an official capacity or allow preparers to include concepts very strictly from these specific taxonomies. This approach greatly reduces the impact on comparability, as the inclusion of these other taxonomies becomes a structured part of the taxonomy itself.</div>
<p class="tdh_072"><i>Impact on Comparability: </i>High</p>  

<div class="tdh_066"><i>Requires:</i> Custom calculations, definitions, presentations</div>
<p class="tdh_020"><a name="a_Ref16166461"></a><span class="tdh_024">5.4.3     </span>Methods to Display and Consume the Data</p>  

<div class="tdh_066">With the transport model defined, developers can turn their attention to supporting systems. These may include systems to help preparers create XBRL reports, systems to view and store XBRL data, and systems to extract the information from one or more reports for analysis. The development needs for these systems will vary greatly by taxonomy and industry. However, it is important to place the taxonomy in the information supply chain and determine how data will reach this stage and how it is to be used after it.</div>
<div class="tdh_066">It also bears repeating that involving third-party software developers, if third-party software is to be allowed for the taxonomy, is essential during both the taxonomy development process and afterward (see Section 4.6.3). Robust, well-designed supporting systems are key to the taxonomy&#8217;s usability.</div>
<div class="tdh_027"><a name="a_Toc24107555"></a><a name="a_Toc23337701"></a>5.5   Validation</div>
<div class="tdh_066"><a name="c5_validation"></a>Validation has been discussed throughout this handbook. At this stage in the development process, developers should begin to lay the groundwork for validation rules and guidelines. The next sections outline some topics developers should explore. It also bears some consideration that if the validation rules become large or complex enough, the creation of a <i>data quality committee</i> may become appropriate. More on how to form such a committee, document data validation rules, and maintain data quality governance is discussed in Chapters 7 and 8.</div>
<div class="tdh_066">It should be mentioned again that XBRL does not natively <i>check </i>its own syntax or data integrity. Software solutions are required to provide preparers and other users with validation tools, which should make use</div>
<p><!-- Field: Page; Sequence: 82 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->77<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">of XBRL&#8217;s structure and relationships. These solutions can also aid developers in designing a robust transport model.</div>
<p class="tdh_020"><span class="tdh_024">5.5.1     </span>Basic Syntax Validation</p>  

<div class="tdh_066">No matter the transport method, there is some syntactic validation inherent to the structure of the data. CSV provides the least robust validation, while XBRL in JSON and XML can be parsed by most applications that parse basic JSON and XML and have their syntax evaluated. As stated in Section 5.4.1, this is an advantage of these formats, particularly XBRL as XML.</div>
<p class="tdh_020"><span class="tdh_024">5.5.2     </span>Data Type Validation</p>  

<div class="tdh_066">Again, data type validation, or ensuring the type of data of the value matches the data type of its concept core dimension, is inherent to XBRL as XML. This type of validation helps ensure the correct kind of fact data is being represented in the report. Textual data should not appear in a numeric fact, for example. Any XML parser will be able to validate these relationships, even for custom data types.</div>
<p class="tdh_020"><span class="tdh_024">5.5.3     </span>Concept Relationship-based Validation</p>  

<div class="tdh_066">XBRL&#8217;s nature proffers validation through its concept relationships. These include, but are not limited to, relationships defined by calculation, definition, and presentation linkbases. The relationship arcs connecting concepts can aid developers (and preparers) in ensuring both the semantic logic of the relationship and that the concepts involved are used properly. A basic XML software application may not be able to check the consistency of relationships, but XBRL software, such as Arelle (which is available free of charge), can aid developers in mapping out concept relationships to ensure illogical or circular relationships do not exist.</div>
<div class="tdh_066">Any software solutions designed for a taxonomy for preparers should make use of at least basic concept relationship-based validation. For example, a calculation of a total sum from its constituent values should be mathematically correct (the fact value for the total should be the sum of the other facts in the calculation arc). Implementing this type of validation will aid preparers in avoiding mistakes.</div>
<p class="tdh_020"><span class="tdh_024">5.5.4     </span>Regulatory/Industry Requirements</p>  

<div class="tdh_066">Regulatory requirements and/or industry standards, such as specific business rules, can be applied through custom validation created for the taxonomy. These will vary from situation to situation. Validation rules should be well-documented and available to users along the information supply chain (see Chapter 7). Preparers should be encouraged to make use of them in validating their reports. Many validation rules can be built into software applications so that preparers can check the XBRL report automatically to identify errors. Creating and incorporating automated business rules can improve the quality, accuracy, and consistency of data produced in XBRL reports.</div>
<p><!-- Field: Page; Sequence: 83 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->78<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt; float: right; margin: 8px; border: 1px solid #e2e2e2; border-bottom: none;"><a href="#toc">Table of Contents</a></div>
<div class="tdh_028"><a name="a_Toc24107556"></a><a name="a_Toc23337702"></a><a name="a_Ref18055582"></a>6   The Mechanics of Taxonomy Development</div>
<div class="tdh_066"><a name="a_dfkhfopxryfc"></a>With the transport model now clearly defined, the focus turns to the process of actually building the XBRL taxonomy. This chapter describes this process through the free tools available to developers. It also provides suggestions to aid in the physical development process for the taxonomy. Though this chapter investigates the mechanics of taxonomy development through the software available without purchase, developers are encouraged to also explore the various commercial tools that can be used to create, view, and validate an XBRL taxonomy. Commercial tools provided by XBRL US and XBRL International members can be found at these sites: <a href="https://xbrl.us/home/learn/tools-and-services/"><span class="tdh_035"><i><u>XBRL US Member Tools &amp; Services</u></i></span></a> and <a href="https://www.xbrl.org/the-standard/how/tools-and-services/"><span class="tdh_035"><i><u>XBRL International Tools &amp; Services</u></i></span></a>. Even if developers opt to use commercial tools or other software approaches not described here, reading through this chapter may be helpful as it will provide insights into the methodology of generating a taxonomy.</div>
<div class="tdh_027"><a name="a_Toc24107557"></a><a name="a_Toc23337703"></a>6.1   Workflow</div>
<div class="tdh_066">Before beginning work on the taxonomy itself, developers should design the <i>workflow </i>(see Figure 6-11 for an example). Creating an XBRL taxonomy often requires multiple individuals and organizations working together in a single, collaborative workspace, and each of these parties may perform different duties and require different levels of access. For example, some individuals or a group may be tasked with transforming the logical data model into a beta taxonomy. Another may be in charge of incorporating regulatory/governance changes, both for the initial taxonomy and as future changes occur. A third group may handle reading reviewers&#8217; comments and making recommendations for modifications. Each of these groups may require different levels of access to the taxonomy itself. Those responsible for adding and revising content should have edit access; those reviewing content may be given only view and comment access to guard against inadvertently corrupting creation files. All members of the working group should be able to review the work in progress.</div>
<div class="tdh_066">In addition, taxonomy developers may wish to employ version control software to track changes to the taxonomy as a whole. This is particularly important if the taxonomy is large or has many individuals or groups contributing to it.</div>
<p class="tdh_099"><img class="tdh_155" src="http://files.xbrl.us/images/tdh/tdh_p1_039.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref20224385"></a>Figure 6-1. An example taxonomy workflow diagram</p>  

<div class="tdh_027"><a name="a_Toc24107558"></a><a name="a_Toc23337704"></a><a name="a_ftoazpo3ygfo"></a>6.2   Preparing and Generating the Taxonomy</div>
<div class="tdh_066"><a name="c6_taxonomy_creation"></a>The following sections walk through the steps to generating a taxonomy using freely available software. Again, developers can choose to use other solutions, though these general steps will remain constant no</div>
<p><!-- Field: Page; Sequence: 84 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->79<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">matter which software packages are employed. Also, it bears mentioning that XBRL schema and linkbase files are merely text files (ASCII), so they can be created and edited in any text or XML editor. With a sufficient knowledge of XML, one can craft these documents with no outside assistance from a spreadsheet or XBRL management application.</div>
<p class="tdh_020"><a name="a_w5hihckdwfqd"></a><span class="tdh_024">6.2.1     </span>Introduction to Development with Arelle</p>  

<div class="tdh_066">Arelle<a class="tdh_040" href="#note_ftn3" name="note_ftnref3">3</a>, which was briefly discussed in Section 1.4.2, is a freely available XBRL development and management solution. Arelle is open source and has tools to help developers organize, visualize, and create taxonomy schema and linkbase files. Arelle can also aid preparers with validation and visualization of XBRL reports.</div>
<div class="tdh_066">In terms of development, Arelle offers a plugin that allows developers to design their taxonomy using an Open Office XML spreadsheet. Many spreadsheet applications, including Microsoft Excel and Google Sheets, natively support this format. In addition to facilitating easier organization of the taxonomy, using a spreadsheet also supports collaboration since many of these software platforms have collaborative features built into them.</div>
<div class="tdh_066">To facilitate the process of taxonomy development, XBRL US has developed a <span class="tdh_033">Google Sheets template</span>, known as the <i>Taxonomy Development Template</i>, which is pre-formatted with formulas. Arelle also permits exporting any taxonomy into a spreadsheet, which gives developers a chance to see what a complete taxonomy looks like in spreadsheet format. Developers can also delete the concepts and relationships but leave the overall spreadsheet structure to create their own template. This guide will walk through developing the widget taxonomy using a spreadsheet format. This taxonomy can be downloaded from XBRL US here: <a href="https://files.xbrl.us/documents/TDH-Ch5-Widget-Taxonomy.xlsx"><span class="tdh_035"><i><u>https://files.xbrl.us/documents/TDH-Ch5-Widget-Taxonomy.xlsx</u></i></span></a>. Developers can modify this taxonomy to create their own using the steps outlined below. In addition, developers can use this template in Arelle to generate schema and linkbase files to examine and change as they wish.</div>
<p class="tdh_020"><a name="a_Ref22841357"></a><span class="tdh_024">6.2.2     </span>Building a Taxonomy with a Spreadsheet</p>  

<div class="tdh_066">The widget taxonomy spreadsheet contains the structure needed to generate a taxonomy. Sample data is included in the spreadsheet which should be replaced by the developer.<a name="a_Ref20138568"></a> Orange cells represent column headers and should not be edited.</div>
<div class="tdh_066">The taxonomy development spreadsheet contains two sheets: a sheet entitled Concepts and a Discoverable Taxonomy Set (DTS) sheet. The developer will customize each of these sheets to reflect the new taxonomy. Each sheet is described in the subsequent sections. Note that Arelle only uses the content of the cells to generate a taxonomy. Therefore, developers are encouraged to use formatting and indenting to help make the sheets clearer, more organized, and easier to read.</div>
<p class="tdh_026"><a name="a_Ref24105962"></a><a name="a_tyzi18z4dwu6"></a>6.2.2.1     Concepts Sheet</p>  

<div class="tdh_066"><a name="c6_concepts_sheet"></a>This sheet contains a list of every concept to be used in the taxonomy, along with its associated properties. Because the taxonomy is in XML format, concepts are represented by one or more elements. In this chapter, the terms concepts and elements are often used interchangeably. This section will break the concept sheet down into three sections: columns A through D, which are related to the concept labels and overall structure (Figure 6-2 and Table 6-1), columns E through L, related to the concept properties (Figure 6-3 and Table 6-2), and columns M through P, related to concept relationships (Figure 6-4 and Table 6-3).</div>
<hr class="tdh_260" align="left" size="1" />
<div class="tdh_066"><a class="tdh_040" href="#note_ftnref3" name="note_ftn3">3</a> Learn more about Arelle and download it here: <a href="http://arelle.org/"><span class="tdh_035"><i><u>http://arelle.org/</u></i></span></a></div>
<p><!-- Field: Page; Sequence: 85 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->80<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_099"><img class="tdh_119" src="http://files.xbrl.us/images/tdh/tdh_p1_040.jpg" alt="A screenshot of a cell phone Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref23243671"></a>Figure 6-2. The Concepts Sheet columns related to concept labels</p>  

<table class="tdh_239" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_205">
<td class="tdh_016"><b>A</b></td>
<td class="tdh_013">Presentation Label</td>
<td class="tdh_013" colspan="2">The label used on the current presentation for this concept. This only appears in an XBRL viewer that renders the presentation.</td>
</tr>
<tr>
<td class="tdh_227"><b>B</b></td>
<td class="tdh_220">Standard Label</td>
<td class="tdh_229">The default label for the concept. All concepts should have a standard label.</td>
<td class="tdh_004"></td>
</tr>
<tr class="tdh_205">
<td class="tdh_005"><b>C</b></td>
<td class="tdh_006">Terse Label</td>
<td class="tdh_006" colspan="2">The shortened version of the standard label. This column is optional.</td>
</tr>
<tr>
<td class="tdh_213"><b>D</b></td>
<td class="tdh_215">Verbose Label</td>
<td class="tdh_215">The enhanced version of the standard label. This column is optional.</td>
<td class="tdh_182"></td>
</tr>
</tbody>
</table>
<p class="tdh_106"><a name="a_Ref23243693"></a>Table 6-1. Descriptions of the Concepts Sheet columns related to concept labels</p>  

<p class="tdh_099"><img class="tdh_118" src="http://files.xbrl.us/images/tdh/tdh_p1_041.jpg" alt="A screenshot of a cell phone Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref23243761"></a>Figure 6-3. The Concepts Sheet columns related to concept properties</p>  

<p><!-- Field: Page; Sequence: 86 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->81<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<table class="tdh_239" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_205">
<td class="tdh_016"><b>E</b></td>
<td class="tdh_013">Prefix</td>
<td class="tdh_013">The name of the taxonomy to which the concept belongs. This prefix is set on the DTS sheet discussed below.</td>
</tr>
<tr>
<td class="tdh_227"><b>F</b></td>
<td class="tdh_220">Name</td>
<td class="tdh_229">The name of the concept (element name). This is the actual XML tag.</td>
</tr>
<tr class="tdh_205">
<td class="tdh_005"><b>G</b></td>
<td class="tdh_006">Data Type</td>
<td class="tdh_006">The data type of the concept. Types must be entered in a qualified name format (prefix:type).</td>
</tr>
<tr>
<td class="tdh_213"><b>H</b></td>
<td class="tdh_215">Substitution Group</td>
<td class="tdh_215">The concept&#8217;s substitution group. This indicates the category of the concept (either an <i>item</i>, <i>hypercubeItem</i>, or <i>dimensionItem</i>).</td>
</tr>
<tr class="tdh_205">
<td class="tdh_005"><b>I</b></td>
<td class="tdh_006">Period Type</td>
<td class="tdh_006">The concept&#8217;s period type. It can be either <i>duration</i> or <i>instant</i>.  This property is required if the concept&#8217;s substitution group is <i>item</i>.</td>
</tr>
<tr>
<td class="tdh_213"><b>J</b></td>
<td class="tdh_215">Balance Type</td>
<td class="tdh_215">The concept&#8217;s balance type. The value can be <i>debit </i>or <i>credit. </i>This property only applies if the concept&#8217;s substitution group is <i>item</i>. The balance type is typically only applicable to concepts representing accounting facts.</td>
</tr>
<tr class="tdh_205">
<td class="tdh_005"><b>K</b></td>
<td class="tdh_006">Abstract</td>
<td class="tdh_006">The concept&#8217;s abstract property. It can be other true or false, but it must be true if the concept&#8217;s substitution group is <i>dimensionItem</i> or <i>hypercubeItem</i>.</td>
</tr>
<tr>
<td class="tdh_213"><b>L</b></td>
<td class="tdh_215">Nillable</td>
<td class="tdh_215">The concept&#8217;s nillable property. It can be either true or false, but it must be true if the concept&#8217;s substitution group is <i>dimensionitem</i> or <i>hypercubeItem</i>.</td>
</tr>
</tbody>
</table>
<p class="tdh_106"><a name="a_Ref23243773"></a>Table 6-2. Descriptions of the Concepts Sheet columns related to concept properties</p>  

<p class="tdh_099"><img class="tdh_125" src="http://files.xbrl.us/images/tdh/tdh_p1_042.jpg" alt="A screenshot of a cell phone Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref23243964"></a>Figure 6-4. The Concepts Sheet columns related to concept relationships</p>  

<table class="tdh_239" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_205">
<td class="tdh_016"><b>M</b></td>
<td class="tdh_013">Depth</td>
<td class="tdh_013">The hierarchical level of the concept. These are relative to preceding levels (so the highest level of the presentation is 0, the next level beneath it is 1, and so on).</td>
</tr>
<tr>
<td class="tdh_227"><b>N</b></td>
<td class="tdh_220">Preferred Label</td>
<td class="tdh_229">The preferred label of the concept. The preferred label will appear as the concept&#8217;s label in the presentation. This only appears in an XBRL viewer that renders the presentation.</td>
</tr>
<tr class="tdh_205">
<td class="tdh_005"><b>O</b></td>
<td class="tdh_006">Calculation Parent</td>
<td class="tdh_006">The parent concept of the calculation arc in which this concept is involved. Entering a calculation parent makes the concept of this row in the spreadsheet part of a calculation resulting in the parent.</td>
</tr>
<tr>
<td class="tdh_213"><b>P</b></td>
<td class="tdh_215">Calculation Weight</td>
<td class="tdh_215">The weight applied to the concept in the calculation arc in which this concept is involved. Because XBRL only supports summations through calculation arcs, the value can either be <i>1</i> or <i>-1</i>.</td>
</tr>
</tbody>
</table>
<p class="tdh_106"><a name="a_Ref23243990"></a>Table 6-3. Description of Concepts Sheet columns related to concept relationships</p>  

<p><!-- Field: Page; Sequence: 87 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->82<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_032"><a name="a_Ref22838874"></a>6.2.2.1.1     Adding Presentations</p>  

<div class="tdh_066">Presentations are delineated on the Concepts sheet with the following text: <i>sort code</i> – <i>type</i> – <i>name</i>. The <i>sort code</i> is used to order the presentations. Generally, they are six digits. The first two digits group presentations by their specific semantic meaning, which can vary from taxonomy to taxonomy. The remainder of the digits can be used to represent further grouping or simply to order them within the taxonomy. The <i>type </i>indicates the presentation type, which is &#8220;Statement&#8221; in this case, to refer to the statement of widget revenue. However, developers can define their own types as needed. The <i>name </i>contains the name of the presentation.</div>
<div class="tdh_066">Any number of presentations can appear on the Concepts sheet. Each presentation should begin with an abstract concept that should then group all concepts beneath it. Additional abstract concepts are required for constructs like the domain and axis elements (Figure 6-5).</div>
<p class="tdh_099"><img class="tdh_126" src="http://files.xbrl.us/images/tdh/tdh_p1_043.jpg" alt="A screenshot of a cell phone Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref21685163"></a>Figure 6-5. Presentation depth of the Widget Performance Presentation</p>  

<div class="tdh_066">The presentation for Widget Performance has organizational, container concepts added, such as Widgets Performance [Abstract] and Widgets Performance [Table]. The former is a container concept for the entire presentation and the second is one for this particular table (each presentation can contain any number of tables, though this one only has one). Other container concepts also are required, such as Widget Type [Axis], which defines the taxonomy-defined dimension, and Widget Type [Domain], which contains the allowable members for this taxonomy-defined dimension. Finally, Report [Line Items] contains the concept core dimension for this table: Total Purchases, Total Production Expenses, and Performance of Widget. Note that this table is a combination of three parts of the physical data model (Figure 5-3.): Total Sales, Total Expenses, and Widget Performance. As described in Section 5.3.3, the widget taxonomy lends itself to combining these parts of the data model into a single presentation, since there is no need to report individual widget expenses.</div>
<div class="tdh_066">The depth column in Figure 6-5 describes the level of concept nesting for each concept. Note that the depth level corresponds to the indenting for each concept; this was done to aid viewers in seeing hierarchical structure. Arelle only makes use of the depth column in building presentations.</div>
<div class="tdh_066">The Widget Sales presentation was defined in a similar manner.</div>
<p class="tdh_026"><a name="a_Ref21953124"></a><a name="a_1yn4bc25brg9"></a>6.2.2.2     DTS Sheet</p>  

<div class="tdh_066"><a name="c6_DTS_sheet"></a>The Discoverable Taxonomy Set (DTS) (Figure 6-6) sheet contains all the linkages and references necessary to assemble the taxonomy.</div>
<p><!-- Field: Page; Sequence: 88 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->83<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_099"><img class="tdh_127" src="http://files.xbrl.us/images/tdh/tdh_p1_044.jpg" alt="A screenshot of a cell phone Description automatically generated" /></p>  

<p class="tdh_106"><a name="a_Ref21687102"></a>Figure 6-6. The Discoverable Taxonomy Set (DTS) Sheet for the widget taxonomy</p>  

<div class="tdh_066">This sheet must layout both the files that Arelle needs to use to create the taxonomy and the files it will create to represent the taxonomy.</div>
<p><!-- Field: Page; Sequence: 89 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->84<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<table class="tdh_239" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_205">
<td class="tdh_016"><b>A</b></td>
<td class="tdh_014">Specification</td>
<td class="tdh_015">
<p class="tdh_072">The action Arelle associates with the row. Options are:</p>  

<ul>
<li><span class="tdh_190"><i>colheader</i> – allows the headers on the Concepts Sheet to be custom defined (optional).</span></li>
<li><span class="tdh_190"><i>extension</i> – directs Arelle to create a file using information specified in the rest of the row.</span></li>
<li><span class="tdh_190"><i>generate</i> – directs Arelle to create a file using information specified in the rest of the row (same in functionality as <i>extension</i> and one must be included).</span></li>
<li><span class="tdh_190"><i>include</i> – makes a reference to a namespace contained in the row (such as units or currency codes, for example) (optional).</span></li>
<li><span class="tdh_190"><i>import</i> – indicates the row contains references to other taxonomies or information this taxonomy requires. Base XBRL imports are almost always required to make use of base XBRL data types. Unlike <i>include, import</i> allows the elements of the referenced documents to be used (optional).</span></li>
<li><span class="tdh_190"><i>meta</i> – indicates the row pertains to meta information for the taxonomy (optional).</span></li>
<li><span class="tdh_190"><i>skip rows</i> – delineates rows to be shipped (optional).</span></li>
<li><span class="tdh_190"><i>workbook</i> – indicates that the row contains information for another workbook that should be included in the taxonomy (optional).</span></li>
<li><span class="tdh_190"><i>worksheet</i> – specifies which sections of the spreadsheet should be used to build the taxonomy presentations (optional).</span></li>
<li><span class="tdh_190"><i>xmlns</i> – generates a namespace using the information specified in the row (optional).</span></li>
</ul>
</td>
</tr>
<tr>
<td class="tdh_227"><b>B</b></td>
<td class="tdh_221">File Type</td>
<td class="tdh_229">The type of the file being included or produced. Allowable values include <i>schema, linkbase, </i>and <i>role</i>. If the Specification is <i>meta,</i> this column can contain the type of the meta-data to be added.</td>
</tr>
<tr class="tdh_205">
<td class="tdh_005"><b>C</b></td>
<td class="tdh_007">Prefix (schema), Type (linkbase), Argument (other)</td>
<td class="tdh_008">
<p class="tdh_072">The prefix for the schema or type of the linkbase, depending on the value of <i>File Type</i>. This should match the prefix of any schema or linkbase being added if the Specification is <i>import </i>or <i>include.</i> For the <i>extension</i> or <i>generate</i> Specification, if the File Type is <i>schema</i>, this should include the prefix for the new taxonomy. If the File Type is <i>linkbase</i>, this should include the linkbase types as applicable (<i>label</i>, <i>presentation</i>, <i>calculation</i>, etc.). For the <i>role </i>File Type, this column can be left blank.</p>  

<p class="tdh_072">This column can also contain optional arguments depending on the Specification. For example, if the Specification is <i>meta</i>, this column can hold data values for the attributes listed in the File Type column.</p>  

</td>
</tr>
<tr>
<td class="tdh_213"><b>D</b></td>
<td class="tdh_216">File, HREF, or Role Definition</td>
<td class="tdh_217">
<p class="tdh_072">The location or role definition for the row, depending on the Specification. For the <i>import</i> and <i>include</i> Specifications, this row should contain the location (usually a URI) of the file containing the schema or linkbase. For the <i>generate</i> and <i>extension</i> Specifications, this column will contain the names of the files to be generated.</p>  

<p class="tdh_072">If the File Type is <i>role</i>, this column should contain the name of the taxonomy&#8217;s presentations. This should exactly match the name given on the Concepts Sheet, including the sort code and type.</p>  

</td>
</tr>
<tr class="tdh_205">
<td class="tdh_005"><b>E</b></td>
<td class="tdh_007">Namespace URI</td>
<td class="tdh_006">The unique namespace of the schema/linkbase documents being imported/included or generated. For the taxonomy being created, this should be a domain by which the developers can be publicly referenced.</td>
</tr>
</tbody>
</table>
<p class="tdh_106">Table 6-4. Descriptions of the DTS Sheet columns</p>  

<p><!-- Field: Page; Sequence: 90 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->85<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Note that this reference includes and explains only some of the options that can be used in the spreadsheet in conjunction with Arelle. See the Arelle documentation for more information.</div>
<p class="tdh_032">6.2.2.2.1     Naming Files</p>  

<div class="tdh_066">Files and URIs named in Column D of the DTS Sheet must be syntactically correct. For URIs, the entire URI must be included. For file names, they need not include a local or remote path; Arelle will generate that during the taxonomy creation process. Note that linkbase file names should end with a .xml file extension, and schema file names should end with a .xsd file extension.</div>
<div class="tdh_066">Developers can name the output taxonomy files anything they wish. However, using a suffix, such as &#8220;_lab&#8221; for label linkbases and &#8220;_cal&#8221; for calculation linkbases, can aid in organization (see Figure 6-6).</div>
<p class="tdh_032">6.2.2.2.2     Creating Entry Points</p>  

<div class="tdh_066">Developers can create entry points in the DTS Sheet by creating a &#8220;subgrouping&#8221; in the taxonomy. To do this, the schema document for the taxonomy must be generated again only with a name for the entry point in the File column (column D). The presentations pertinent to this entry point should be listed again beneath it. Arelle will use this information to create another schema (.xsd) file for the entry point that only contains this subset of presentations. Developers should always take care to create a schema document of the entire taxonomy in addition to separate schema files for their entry points.</div>
<div class="tdh_066">Once the spreadsheet is completed, it can be used with Arelle to generate a taxonomy. The next section will explore the basics of using Arelle.</div>
<div class="tdh_027"><a name="a_Toc24107559"></a><a name="a_Toc23337705"></a><a name="a_ntmok9txvje0"></a>6.3   Using Arelle</div>
<div class="tdh_066"><a name="c6_arelle"></a>Arelle provides the XBRL community with an easy to use, open source platform for XBRL. Arelle offers validation, instance creation, and taxonomy generation, among other capabilities. Once the concepts and structures have been prepared in the spreadsheet, Arelle can transform this information into a taxonomy. Note again that Arelle requires the document to be saved as a Microsoft Excel spreadsheet; most freely available spreadsheet programs will save documents in this format.</div>
<div class="tdh_066">Download Arelle at <a href="http://arelle.org/"><span class="tdh_035"><i><u>http://arelle.org/</u></i></span></a> and open it. Arelle has a number of plug-ins that can be sorted and installed by going to <b>Help</b> / <b>Manage Plug-ins</b> via the menu. The plug-in <i>Load from Excel</i> is required for this process (Figure 6-7).</div>
<p><!-- Field: Page; Sequence: 91 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->86<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_106"><img src="http://files.xbrl.us/images/tdh/tdh_p1_figure_67.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref21952617"></a>Figure 6-7. Arelle&#8217;s plug-in manager which the Load from Excel spreadsheet plug-in</p>  

<div class="tdh_066">Once the correct plug-in has been added to Arelle, the taxonomy can be generated by going to <b>File / Open File</b> and selecting the saved spreadsheet locally on the computer. Arelle will ask the user to select a local folder where the taxonomy files that are generated will be placed.</div>
<div class="tdh_066">After the taxonomy has been generated, it will appear in Arelle as shown in Figure 6-8. Validate the taxonomy by clicking on the &#8220;scales&#8221; icon in the task bar (boxed in red in this screen capture).</div>
<p class="tdh_099"><img class="tdh_114" src="http://files.xbrl.us/images/tdh/tdh_p1_045.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref21952841"></a>Figure 6-8. Generating a taxonomy in Arelle</p>  

<div class="tdh_066">Arelle will embed the include/imported information as specified in the DTS sheet and generate schema and linkbase XML documents as required. As stated in the DTS sheet discussion (Section 6.2.2.2), linkbase files are ASCII files with an .xml extension, and schema files are ASCII documents with an .xsd extension. The filenames specified in the DTS sheet should appear here. Developers can create a zip file containing the files that comprise the taxonomy as shown in the illustration below. Remember these files are saved by Arelle into the folder selected during the taxonomy generation process.</div>
<p><!-- Field: Page; Sequence: 92 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->87<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_099"><img class="tdh_117" src="http://files.xbrl.us/images/tdh/tdh_p1_046.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref21957793"></a>Figure 6-9. The contents of a taxonomy zip file generated from Arelle</p>  

<div class="tdh_066">This zip file (Figure 6-9) contains the taxonomy (which in this case has two entry points plus linkbases). Zip files make for easy transport and dissemination.</div>
<div class="tdh_027"><a name="a_Toc24107560"></a><a name="a_Toc23337706"></a><a name="a_la9ofnknakc4"></a>6.4   The Importance of Public Exposure</div>
<div class="tdh_066">At this point, developers have essentially created a beta taxonomy (Figure 6-1). Initial testing should be performed, such as developing test instance documents, better refining and/or implementing data quality rules, and examining difficulties that can arise in any supporting systems. Once the taxonomy has passed this initial testing phase, it should move to a draft taxonomy ready for public review.</div>
<div class="tdh_066">Public exposure is a vital step in the development process. It should be noted that the term &#8220;public&#8221; is relative to the size and scope of the taxonomy. For a large taxonomy involving many preparers, consumers, and potentially regulators, the taxonomy should undergo significant public review (where anyone can see and comment on the taxonomy). For a small taxonomy whose use may be limited to an internal tool in a company, &#8220;public&#8221; review may be limited to the group of users who will interact with the taxonomy (a particular department, for example, or internal auditors). The taxonomy should be made available to all users so that they can review the concepts, examine the relationships between the concepts, understand workflow impact, review data quality rules, and study sample instance documents, among other things.</div>
<div class="tdh_066">A structure for public exposure should allow/include the ability for reviewers to:</div>
<ol>
<li><span class="tdh_190">View the taxonomy in freely available software (Arelle, spreadsheet applications, etc.)</span></li>
<li><span class="tdh_190">Download the taxonomy files in a zip format as a full taxonomy package</span></li>
<li><span class="tdh_190">Access to sample XBRL instance documents generated from this taxonomy</span></li>
<li><span class="tdh_190">Agree to legal terms and conditions related to submitting comments as necessary</span></li>
<li><span class="tdh_190">Post comments</span></li>
<li><span class="tdh_190">View comments from other reviewers</span></li>
</ol>
<div class="tdh_027"><a name="a_Toc24107561"></a><a name="a_Toc23337707"></a><a name="a_y73y7yvb0i2n"></a>6.5   Guidance</div>
<div class="tdh_066">As a reminder, various documents are available from XBRL US and XBRL International that can be helpful in the taxonomy development process. We recommend reading through these before initiating taxonomy development.</div>
<ul>
<li><span class="tdh_190"><a href="https://xbrl.us/xbrl-reference/style-guide/#a_Toc479240431"><span class="tdh_035"><i><u>XBRL US Style Guide</u></i></span></a> — Provides naming styles for element names, labels.</span></li>
<li><span class="tdh_190"><a href="https://xbrl.us/xbrl-reference/tam/"><span class="tdh_035"><i><u>XBRL US Taxonomy Approval Metrics and Process</u></i></span></a> — Establishes standards checklist for the review and approval of XBRL US certified taxonomies.</span></li>
<li><span class="tdh_190"><a href="https://xbrl.us/xbrl-reference/xbrl-specification-index/"><span class="tdh_035"><i><u>XBRL International Specification Index</u></i></span></a> — Contains the XBRL specifications, to which all taxonomies must adhere.</span></li>
</ul>
<p><!-- Field: Page; Sequence: 93 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->88<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt; float: right; margin: 8px; border: 1px solid #e2e2e2; border-bottom: none;"><a href="#toc">Table of Contents</a></div>
<div class="tdh_028"><a name="a_Toc24107562"></a><a name="a_Toc23337708"></a><a name="a_Ref17796694"></a>7   Documenting a Taxonomy</div>
<div class="tdh_066">An XBRL taxonomy is a powerful tool to transport data in a standardized, predictable manner. Like any tool, it can only fulfill its purpose when those who interact with it understand how to use it. Therefore, creating documentation is a vital step in the development of any XBRL taxonomy. All users, from preparers to software designers to regulators and consumers, must be able to navigate the taxonomy to properly use the taxonomy and interpret the data it represents. Documentation is a key part of that process.</div>
<div class="tdh_066">As with many other steps of the taxonomy development process, the amount and breadth of the documentation should depend on the scope of the taxonomy and the number and variety of users who will engage with it. A taxonomy with limited scope, such as a taxonomy meant for internal reporting within a company, may not require as much extensive documentation. A taxonomy that will be relevant to many different people with different levels of familiarity with XBRL may require significantly more user support and guidance. Further, a taxonomy that is simple with a limited number of concepts and that is not extensible may not require as much in-depth explanation as one with thousands of concepts and multiple ways to express the same data. The latter may warrant careful instruction on which approaches are ideal in certain situations.</div>
<div class="tdh_066">The process of writing documentation should be on-going through the development of the taxonomy. In addition to other documents, authors may consider publishing a <i>Taxonomy White Paper</i>. This may be written and made public before the other documents, and it should concisely present the industry problem, the pertinent regulations, requirements, and use cases affecting the project, the options considered, and the taxonomy as a solution. The rationale for selecting XBRL and the overall design choices should be presented. The <i>Taxonomy White Paper </i>can be considered as an announcement of the taxonomy, with explanation of its purpose and justification for its development. This document is meant to introduce the public to the taxonomy and lay the groundwork for eventual adoption. An example template for the <i>Taxonomy White Paper </i>can be found in Appendix C.</div>
<div class="tdh_066">At a minimum, developers should also create a general <i>Taxonomy Guide</i>, which offers an in-depth explanation of structure and contents of the taxonomy, a <i>Preparer Guide</i>, to guide preparers in creating accurate and well-structured reports, and a <i>Data Consumer Guide</i>, to provide detailed examples on how to use the taxonomy to accomplish common use cases. The creation of the <i>Taxonomy Guide</i> can be performed in parallel with the taxonomy, whereas the <i>Preparer Guide</i> and <i>Data Consumer Guide</i> may be written toward the end of process.</div>
<div class="tdh_066">Note that these three guides apply to very separate audiences, which will be discussed in greater detail in this chapter&#8217;s subsequent sections. The make-up and skillset of the audience is a key consideration when crafting any technical document. As an overview, the <i>Taxonomy Guide </i>is aimed at explaining the taxonomy itself in detail, including the design choices (such as allowing extensibility) and rationales behind those choices. This document is meant to be a technical specification and is therefore aimed at taxonomy managers and software developers. This document can serve as both a blueprint during the development of the taxonomy and as a guide for users and developers after the taxonomy has been released. The <i>Preparer Guide</i> is intended to provide preparers with useful information about the taxonomy&#8217;s concept and structures as needed to build XBRL reports. Finally, the <i>Data Consumer Guide</i> is intended to provide information and common use cases for data consumers.</div>
<p><!-- Field: Page; Sequence: 94 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->89<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_099"><img class="tdh_145" src="http://files.xbrl.us/images/tdh/tdh_p1_047.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref23866244"></a>Figure 7-1. Different methods of organizing taxonomy documentation</p>  

<div class="tdh_066">Different methods of organizing taxonomy documentation appear in Figure 7-1. If the developer opts not to create a separate <i>Preparer Guide</i> and/or <i>Data Consumer Guide</i>, the single <i>Taxonomy Guide</i> should cover these topical areas. However, as a rule of thumb, a technical document should not contain a great deal of information not pertinent or relevant to its intended audience. Doing so makes the document difficult to navigate. If between a fourth and a third of the document&#8217;s content is aimed at a different audience than the audience for the rest of the document, creating separate guides should be considered.</div>
<div class="tdh_066">It is also likely that different readers will have different levels of expertise in the XBRL standard. The authors of any XBRL guide should include a section on the <i>XBRL Overview</i> to ensure that all readers have a basic understanding of XBRL. The <i>XBRL Overview</i> should bring novice readers up-to-speed on the constructs of XBRL, such as concepts and the role of taxonomy-defined dimensions, so that they are better equipped to work with the taxonomy. Appendix D contains an example <i>XBRL Overview</i>.</div>
<div class="tdh_066">Finally, as taxonomy updates and releases are introduced and disseminated to its users, developers should take care to create informative and helpful release notes. This is discussed at the end of this chapter.</div>
<div class="tdh_066">All XBRL documentation should include explanatory information, diagrams, illustrations, and references wherever possible. Examples can often help readers relate abstract ideas to familiar real-world instances, and illustrations aid in visualizing complex relationships. As a general rule of thumb, these tools should be employed strategically to help readers digest the document.</div>
<div class="tdh_027"><a name="a_Toc24107563"></a><a name="a_Toc23337709"></a>7.1   How to Use This Chapter</div>
<div class="tdh_066">This chapter provides a framework for the structure and content of a <i>Taxonomy Guide</i>, a <i>Preparer Guide</i>, and a <i>Data Consumer Guide</i>. The subheadings within each section address the general topics that should be included in each type of document. Developers can also refer to Appendix E, Appendix F, and Appendix G for templates of these documents (which are also available for download as Microsoft Word document files from <a href="https://xbrl.us/tdh-templates"><span class="tdh_035"><i><u>https://xbrl.us/tdh-templates</u></i></span></a>). These templates can be used as a basis for constructing documentation. Their outlines exactly match the outlines covered in this chapter. In addition, where possible, &#8220;boiler plate&#8221; text appears in the template to guide authors in beginning their discussion of the relevant topics, in addition to bullet items clearly marked that should be replaced with the appropriate content specific to the taxonomy being documented. In other words, the content that follows in this chapter provides advice and guidance on how to complete these templates, and the corresponding templates contain generic text as well as brief reminders concerning what sort of information should be covered. Authors can choose to forego using these templates or create their own content based on the templates; the guidance in this chapter will still be helpful in determining what sorts of information should be discussed in the guides and how it should be organized.</div>
<p><!-- Field: Page; Sequence: 95 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->90<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Documentation needs will, of course, vary from taxonomy to taxonomy. Therefore, this chapter and the templates in the appendices are meant to establish a general outline of what these documents may contain to aid readers in understanding XBRL and the XBRL taxonomy. Some of the following sections may not be applicable to every situation, and some may require more in-depth discussion than is indicated here. It is up to the developers and authors of the documentation to determine the nature and depth of the content for each guide.</div>
<div class="tdh_027"><a name="a_Toc24107564"></a><a name="a_Toc23337710"></a><a name="a_Ref22204125"></a>7.2   The <i>Taxonomy White Paper</i></div>
<div class="tdh_066"><a name="c7_taxonomy_white_paper"></a>The <i>Taxonomy White Paper </i>should present the taxonomy to an average reader. This brief document is meant to introduce the data reporting problem in the industry or company (i.e., reason the taxonomy was developed), other potential solutions, and the taxonomy as an answer to this dilemma. Authors may wish to present a cursory discussion of the relevant requirements, regulations, and use cases that influence the industry problem. A short, unbiased description of the alternative solutions can be presented, leading into the discussion of how the XBRL taxonomy is the optimal solution. This document is not a technical one and should not delve into details about the taxonomy. Rather, it is meant to give a reader who is perhaps uneducated with XBRL but who understands the dilemma and needs of the industry, a foundation to understand why the new taxonomy is necessary. More than other documents, the <i>Taxonomy White Paper</i> can be written with a more persuasive tone to clearly indicate to readers that the new XBRL taxonomy is a strong solution to the problems presented.</div>
<div class="tdh_066">An example template for a <i>Taxonomy White Paper</i> appears in Appendix C.</div>
<div class="tdh_027"><a name="a_Toc24107565"></a><a name="a_Toc23337711"></a>7.3   The <i>Taxonomy Guide</i></div>
<div class="tdh_066"><a name="c7_taxonomy_guide"></a>The <i>Taxonomy Guide</i> is the most basic and important document concerning the explanation of the taxonomy itself. The audience for the <i>Taxonomy Guide</i> is those who need to have an in-depth understanding of all aspects of the taxonomy independent of any particular use case. This document will explain the structure of the taxonomy, indicate the way in which the taxonomy represents and validates data, and elucidate how the transport model operates at its most fundamental levels. This information is key to those who will be managing or overseeing the taxonomy itself as well as third-party software developers who must design robust software solutions that can employ the taxonomy to provide high quality data.</div>
<p class="tdh_020"><span class="tdh_024">7.3.1     </span>Goals</p>  

<div class="tdh_066">This section clearly describes the overall goals of the <i>Taxonomy Guide</i> to the readers, which were stated in this document in the previous section. This section should also include a description of the target audience of the <i>Taxonomy Guide </i>and may indicate the level of familiarity these readers should have with industry and regulatory standards. For example, for a financial reporting taxonomy, the <i>Taxonomy Guide</i>&#8216;s target readers may be developers who are familiar with US GAAP financial statement preparation.</div>
<p class="tdh_026">7.3.1.1     Revision History</p>  

<div class="tdh_066">Authors should mention that the document is subject to periodic revision in addition to describing its revision history. The governance process should be briefly described as it pertains to taxonomy and documentation updates so that readers are aware changes can be made and how those changes will be implemented.</div>
<p class="tdh_020"><a name="a_Ref17796911"></a><span class="tdh_024">7.3.2     </span>Introduction to the Taxonomy and an Overview of XBRL</p>  

<div class="tdh_066">Authors should begin by introducing the taxonomy and its purpose at a very high level. Readers should be aware of why the taxonomy exists, the types of data it is meant to represent, and its place along the information supply chain of the industry or business sectors for which it has been developed. In addition, authors should include the <i>XBRL Overview</i> (Appendix D), for which XBRL US has provided a pre-constructed template. This section should provide a basic primer on XBRL so that readers unfamiliar with the standard can quickly come up to speed with its basic constructs and usages.</div>
<p><!-- Field: Page; Sequence: 96 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->91<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_020"><span class="tdh_024">7.3.3     </span>Scope</p>  

<div class="tdh_066">Before describing the taxonomy, authors and developers should consider outlining the factors that drove how the taxonomy was developed. This discussion may describe functional and non-functional requirements, the use cases that the taxonomy is designed to represent, and other regulatory and development considerations. This section may also explain the underlying documents, databases, and reports that support the requirements, use cases, and design choices. In summary, this section should address the overall development project scope and considerations as discussed in Chapter 4.</div>
<p class="tdh_020"><span class="tdh_024">7.3.4     </span>Key Features and Structure</p>  

<div class="tdh_066">This section is intended to highlight important features of the taxonomy that users should understand when working with the taxonomy. Some of these issues may be covered in greater detail later in the <i>Taxonomy Guide</i>; this section should provide a brief introduction, not a comprehensive discussion. Note that the template provided in Appendix E breaks some of these topics into subsections; this is a documentation choice and authors should organize information in a way suitable for them.</div>
<div class="tdh_066">Examples of questions that may be addressed include:</div>
<ul>
<li><span class="tdh_190">Has the taxonomy integrated other standards?</span></li>
<li><span class="tdh_190">Are preparers allowed to use extensions with the taxonomy?</span></li>
<li><span class="tdh_190">Is the taxonomy open source and freely available?</span></li>
<li><span class="tdh_190">How is the taxonomy structured? Here authors may provide a short overview of the entry points and presentations and briefly discuss how they are designed to facilitate use of the taxonomy. Authors may also give an indication of the size of the taxonomy.</span></li>
<li><span class="tdh_190">How can content in the taxonomy, and data produced using the taxonomy, be accessed? For example, through APIs, XBRL instance documents.</span></li>
<li><span class="tdh_190">What is the plan for taxonomy maintenance and support?</span></li>
</ul>
<p class="tdh_020"><span class="tdh_024">7.3.5     </span>The Transport Data Model</p>  

<div class="tdh_066">The next section of the <i>Taxonomy Guide</i> should provide a detailed explanation of the reporting domain and the information flow that the taxonomy is designed to capture. This directly describes the transport data model.</div>
<div class="tdh_066">As stated in Chapter 2.1.2, the transport data model <span class="tdh_001">defines the meaning of data within the context of its interrelationships with other data. While this concept has been discussed in depth in this document, readers of the <i>Taxonomy Guide </i>may not be as familiar with the purpose of a transport data model. Authors should explain that the transport data model may reflect aspects of business semantic data models on both the preparers&#8217; and consumers&#8217; sides, but the transport model is independent of both and designed to transmit data from preparers to consumers in a predictable, self-describing, pre-determined manner. The nature of this transport model and how the taxonomy expresses that model should be explained here. This may, again, involve a brief discussion of pertinent requirements, regulations, and use cases. The discussion can also feature a discussion and possibly a graphical representation of the data supply chain specific to this taxonomy.</span></div>
<p class="tdh_020"><span class="tdh_024">7.3.6     </span>Detailed Review of the Taxonomy</p>  

<div class="tdh_066">This section of the <i>Taxonomy Guide</i> provides an in-depth walkthrough of the structure and content of the taxonomy. This section should form the bulk of the <i>Taxonomy Guide</i> and provide readers with detailed information on how to use the taxonomy to create and process XBRL reports.</div>
<p class="tdh_026">7.3.6.1     Taxonomy Physical Structure</p>  

<div class="tdh_066">With the transport data model understood by readers, this section can articulate how the taxonomy represents that model. Because this topic is so important, authors and developers should take care to ensure their explanations of the rationales behind the taxonomy&#8217;s design choices are clear. A solid comprehension of how the overall structure of the taxonomy encapsulates the data model is key to using the taxonomy and developing software to help users interact with it.</div>
<p><!-- Field: Page; Sequence: 97 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->92<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Using both diagrams and text, the section should describe the structure of the taxonomy in detail, including presentations and entry points. Authors and developers may describe why these groupings were created, what they are designed to capture, and who is the target audience for each. For example, if a form was used extensively in a use case supported by the taxonomy, an entry point may encompass concepts related to that form. Similarly, if data represented by the taxonomy is derived from databases, entry points may represent concepts related by database tables. The approach, or multiple approaches taken, should be explained here in detail so that readers can understand how the taxonomy structure services the data itself.</div>
<div class="tdh_066">As with most aspects of documentation, the size and scope of the taxonomy should dictate the level of detail and explanation required to ensure understanding. Large taxonomies, such as the Orange Button Taxonomy which has over 4,000 concepts, may need to be explained by grouping content into logical &#8220;sections&#8221; and providing an in-depth review of each section. Logical sections may be entry points, presentations, tables, or even abstract concepts if this grouping is complex enough to merit further detail. Smaller taxonomies, such as the Surety Work In Process Taxonomy which has approximately 60 concepts, may be handled differently. In a smaller taxonomy, authors can spend more time on detailed descriptions of each category of data, describing the meaning of the concepts and how they work within the limited number of tables.</div>
<p class="tdh_026">7.3.6.2     Concepts</p>  

<div class="tdh_066">This section should address the concepts in the taxonomy and how they relate to common information in the field, industry, or business sector. Depending on the size and scope of the taxonomy, the discussion could be in-depth or cursory. The relationships the concepts have to the entry points, presentations, and the originating documents or databases should be explored as necessary. Authors should explain how some concepts are concept core dimensions (which directly relate to the fact and dictate the fact&#8217;s properties) and how other concepts are abstract and meant to group data. In addition, authors may wish to briefly explore concept properties, particularly labels as these will be specific to the taxonomy and industry.</div>
<p class="tdh_026">7.3.6.3     Dimensions</p>  

<div class="tdh_066">The dimensionality of tables within each section of the taxonomy should be described in detail, including core XBRL dimensions (allowable units, entities, etc.), how to use the taxonomy-defined dimensions that comprise the table, and whether the taxonomy-defined dimensions are typed or explicit. In addition, the rationales behind the design decisions should be explained. Why was a typed or explicit dimension chosen? What do the taxonomy-defined dimensions and their members represent? If there are multiple XBRL dimensions, how would the preparer use those axes? How should table line items be represented? These questions should be properly answered so that readers can understand how the taxonomy represents dimensional data.</div>
<div class="tdh_066">Again, the size of this section depends on the complexity and scope of the taxonomy. For a very large taxonomy, if many of the tables contain similar dimensional structures, an exemplar table can be explained in greater detail to illustrate the structure with a briefer discussion as to how this structure applies elsewhere. Tables can also be grouped in the discussion if they represent similar data and dimensionality. The goal is, as always, explaining the relevant information with as little duplicative or redundant material as possible.</div>
<p class="tdh_026">7.3.6.4     Calculations (Optional)</p>  

<div class="tdh_066">If the taxonomy contains calculations, this section should include an explanation of the calculation relationships between concepts. Each calculation and its implications on validating fact values should be explained, as well as the rationale for including the calculations if applicable.</div>
<p class="tdh_026">7.3.6.5     Formulas (Optional)</p>  

<div class="tdh_066">If the taxonomy contains formulas, this section should include an explanation of the formula relationships between concepts. Each formula and its implications on validating fact values should be explained. In addition, authors may explain why the formulas were designed and included.</div>
<p><!-- Field: Page; Sequence: 98 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->93<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_026">7.3.6.6     Data Types and Units</p>  

<div class="tdh_066">The <i>Taxonomy Guide</i> should include a listing of the kinds of standard data types used (for example, string, monetary, Boolean, etc.) and why they were selected to represent fact data. Developers and authors should discuss in detail any non-standard or custom data types. For example, in the Orange Button Taxonomy, many electricity-related non-standard data types are included, such as energyItemType, powerItemType, and insolationItemType. This taxonomy also contains custom data types, such as the data type &#8220;moduleItemType&#8221; which was created to give preparers options to choose from a list of module technologies. These data types and their usages should be discussed.</div>
<div class="tdh_066">Authors should also discuss unit core dimensions, their usage, and where they are required.</div>
<p class="tdh_026">7.3.6.7     Cross-use of Concepts (Optional)</p>  

<div class="tdh_066">As discussed in Section 2.4.2, concepts can appear in more than one section of a taxonomy because they may be applicable to multiple reporting situations. This should be explained as it pertains to the taxonomy being documented.</div>
<p class="tdh_026">7.3.6.8     Taxonomy References (Optional)</p>  

<div class="tdh_066">In the <i>XBRL Overview</i> section (see Section 7.3.2), authors will have explained what domain-specific standards are used in the taxonomy, if any. In this section of the <i>Taxonomy Guide</i>, authors may take a second opportunity to explore more deeply why those standards were used and how they help provide greater context to the individual concepts.</div>
<p class="tdh_026">7.3.6.9     Linkbase Types</p>  

<div class="tdh_066">Authors should discuss the linkbases used within the taxonomy in this section. At this point, many of the presentations, definitions, calculations, labels, and reference types may have already been discussed. Those that have not been covered should be described here as applicable. Authors may also wish to show how the linkbases define these various relationships through arcs.</div>
<p class="tdh_020"><span class="tdh_024">7.3.7     </span>Transport Format and Instance Preparation</p>  

<div class="tdh_066">The transport format and how to prepare robust instance documents are topics more suitably explored in detail in the <i>Preparer Guide</i> (see Section 7.4)<i>.</i> However, authors should provide a quick overview of the transport format (whether XML, JSON, or CSV has been chosen, for example, and the reasoning behind the decision), if applicable and relevant to the taxonomy&#8217;s use. Authors also should discuss how that format can be used to prepare instance documents. Any considerations that arise from the transport format in terms of using the taxonomy or creating reports should be discussed. Finally, authors should briefly describe any pertinent systems involved in the creation and/or transmission of an XBRL report built with the taxonomy (for example, in the case of financial reporting to the SEC, <i>Taxonomy Guide </i>authors may want to introduce the purpose and mechanics of the EDGAR system that preparers use to submit their XBRL filings to regulators).</div>
<p class="tdh_020"><span class="tdh_024">7.3.8     </span>Using Validation</p>  

<div class="tdh_066">Validation is key to data integrity and usability. Therefore, this part of the <i>Taxonomy Guide</i> should have an extensive discussion of how taxonomy managers and other developers can use the taxonomy structure to aid in validating the data the taxonomy represents. Calculations and formulas should be revisited here and how software solutions could be implemented to ensure these relationships between concepts hold true for the values reported. The use of proper data typing can be mentioned again. Authors should also carefully discuss external validation and regulatory frameworks and how they can be applied. For example, the US Securities and Exchange Commission provides special validation rules that check that an XBRL document created with the US GAAP or IFRS taxonomies is valid and can be accepted by the SEC&#8217;s EDGAR system. These sort of industry-specific considerations should be detailed here to explain how the taxonomy can maintain data integrity as it is transmitted from preparers to consumers.</div>
<p><!-- Field: Page; Sequence: 99 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->94<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_020"><span class="tdh_024">7.3.9     </span>Software Development</p>  

<div class="tdh_066">A key audience of the <i>Taxonomy Guide</i> may likely be software developers, depending on if the taxonomy developers and regulators permit third-party software development. If the XBRL implementation is public-facing and has numerous users and applications, it will probably rely on third-party software to help preparers create XBRL reports. The more software choices there are available to preparers, the less expensive and burdensome the XBRL adoption process becomes.</div>
<div class="tdh_066">If external software development is not allowed, authors should state that here. If it is, authors should cover information pertinent to creating software solutions that view the taxonomy, prepare instance documents, use XBRL-formatted information in subsequent data analyses, or aid users in extending the taxonomy. As with many topics in the <i>Taxonomy Guide, </i>the nature of the industry and the taxonomy itself should drive this discussion. For instance, if aiding preparers in structuring their data and creating XBRL reports is likely to be a major source of software development, authors may want to devote more discussion to aspects of the taxonomy that are relevant to this topic (such as how to implement validation based on calculations and formulas or how to guide users in selecting the correct concepts to represent their data).</div>
<div class="tdh_066">In addition, authors may want to indicate what resources are available to help developers test their software applications (access to the XML schemas, test XBRL instance documents, etc.). If applicable, providing an environment supportive to third-party software development can aid tremendously in facilitating and encouraging the use of the taxonomy to create robust XBRL reports, which is the goal of most stakeholders in the information supply chain.</div>
<p class="tdh_020"><span class="tdh_024">7.3.10     </span>References and Other Resources</p>  

<div class="tdh_066">In this concluding section, authors should explain what references were used in developing and documenting the taxonomy. Reference materials that may be used and may be helpful to other users and developers include the <i>XBRL US Style Guide</i>, this <i>XBRL US Taxonomy Development Handbook</i>, the current <i>XBRL Technical Specifications</i> and <i>Open Information Models</i>, as well as industry specific resources that may have influenced the creation and use of the taxonomy.</div>
<div class="tdh_066">Authors may also consider including further ways readers can educate themselves concerning XBRL and the taxonomy, including the <i>Preparer Guide </i>and the <i>Data Consumer Guide </i>if these documents are separate from the <i>Taxonomy Guide</i> and available. Authors should also include ways to contact the taxonomy developers and governance committees as applicable so that users can receive responses to comments, questions, and concerns.</div>
<div class="tdh_027"><a name="a_Ref14764162"></a><a name="a_Toc24107566"></a><a name="a_Toc23337712"></a>7.4   The <i>Preparer Guide</i></div>
<div class="tdh_066"><a name="c7_preparer_guide"></a>The <i>Preparer Guide</i> is intended to guide preparers through the process of creating XBRL reports using the taxonomy. Oftentimes this document is part of the <i>Taxonomy Guide </i>itself, but it should be separated if it is long and complicated enough that the information is not applicable to both the development and preparation audiences.</div>
<p class="tdh_020"><span class="tdh_024">7.4.1     </span>Goals</p>  

<div class="tdh_066">This section clearly describes the overall goals of the <i>Preparer Guide</i> to the readers. Additionally, authors should describe the target audience for the <i>Preparer Guide </i>and may indicate the level of familiarity these readers should have with industry and regulatory standards. For example, for a financial reporting taxonomy, the <i>Preparer Guide</i>&#8216;s target readers may be filing agents and/or registrants with federal reporting agencies who are familiar with the preparation of financial statements in accordance with US GAAP.</div>
<p class="tdh_026">7.4.1.1     Revision History</p>  

<div class="tdh_066">Authors should mention that the document is subject to periodic revision in addition to describing its revision history. The governance process should be briefly described as it pertains to taxonomy and documentation updates so that readers are aware that changes can be made and how those changes will be implemented.</div>
<p><!-- Field: Page; Sequence: 100 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->95<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_020"><span class="tdh_024">7.4.2     </span>Introduction to the Taxonomy and an Overview of XBRL</p>  

<div class="tdh_066">Authors should begin by introducing the taxonomy and its purpose at a very high level. Readers should be aware of why the taxonomy exists, the types of data it is meant to represent, and its place along the information supply chain for the industry or business sectors for which it has been developed. Additionally, in the <i>Preparer Guide</i> there should be a discussion of the regulatory requirements that may apply to the taxonomy and the XBRL reports created with it. Finally, authors should indicate if the taxonomy allows extensibility and, if so, what sorts of XBRL constructs are extensible. This should be in brief terms; remind readers that greater discussion of extensibility occurs later in the document (as appropriate).</div>
<div class="tdh_066">Authors should include the <i>XBRL Overview</i> (Appendix D), for which XBRL US has provided a pre-constructed template. This section should provide a basic primer on XBRL so that readers unfamiliar with the standard can quickly come up to speed with its basic constructs and usages.</div>
<p class="tdh_020"><a name="a_Hlk17286732"></a><span class="tdh_024">7.4.3     </span>Transforming Previous Data to XBRL</p>  

<div class="tdh_066"><a name="c7_data_set_preparation"></a>A major focus of the <i>Preparer Guide </i>is to provide guidance on taking the current way in which a preparer&#8217;s data is presented, stored, and organized, and formatting it in XBRL for the purposes of generating a well-structured XBRL report. Therefore, a significant portion of the guide should be devoted to mapping data as it has been previously structured in the industry (such as forms currently employed in the reporting process) to the new XBRL transport data model. This is likely to be one of the fundamental sources of confusion and concern for preparers who are newly faced with creating XBRL reports out of their normal data workflow, so it is a good idea to spend some of the documentation offering a clear, concise explanation of how the taxonomy represents the data with which preparers are already familiar.</div>
<p class="tdh_026">7.4.3.1     Originating Data, Documents, and Forms</p>  

<div class="tdh_066">As a first step, authors should explain what originating information is represented by the taxonomy. This includes legacy reporting forms, documents, presentations, databases, and other sources of reportable information. This lays the foundation for gathering the necessary data to construct an XBRL report. Again, if there are governmental or non-governmental regulatory considerations, this should be discussed so preparers can be aware of what information is required in the XBRL report.</div>
<p class="tdh_026">7.4.3.2     Data Preparation</p>  

<div class="tdh_066">Given the originating data, authors should guide preparers through readying the data for transformation to XBRL. This may include topics such as: document transformation from one format to another (such as organizing data in a word processor or spreadsheet or exporting data sets from a database to delimited list files), performing clean-up functions on the data (such as ensuring all information is presented in the proper character set for XBRL transmission and is properly formatted), and ensuring style and presentation choices conform to whatever standards are in place if inline XBRL is to be used.</div>
<div class="tdh_066">In addition, assessing data integrity at this early level should be emphasized. Authors may wish to remind preparers that, while XBRL and XBRL software may provide some measures of validation, the complete accuracy of any particular data set cannot be monitored. It is up to the preparers to ensure the facts being reported are correct. Thus, preparers can take time at this stage to reduce the number of missing data points, check that mathematical relationships are correct and meaningful, and generally ensure the contextual information is accurate. Taking these steps before transforming data to XBRL can reduce the likelihood of &#8220;garbage in, garbage out&#8221; and potentially decrease the difficulty in spotting errors later on, when human-readability may be significantly reduced.</div>
<p class="tdh_026">7.4.3.3     Provided Preparation Software (Optional)</p>  

<div class="tdh_066">Many XBRL implementations will rely on numerous software applications available on the market. In such implementations and depending on the situation, the <i>Preparer Guide</i> may provide a generic discussion of XBRL report preparation without specifying certain applications. Guidance provided should be common throughout the various possible applications. For example, proper use of typed and explicit XBRL dimensions is a task that will need to be followed when working with any software application. The</div>
<p><!-- Field: Page; Sequence: 101 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->96<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">process may be slightly different from application to application, but the underlying decisions will be the same.</div>
<div class="tdh_066">Depending on the availability of third-party software and if that software is endorsed, recommended, or developed by the taxonomy regulators, authors may wish to mention the advantages of using it. Again, for generic software, authors should probably not endorse one solution over another.</div>
<div class="tdh_066">If provided software exists, authors may wish to integrate a guide to using that software as part of this document. Tying the discussion of the following topics directly into the software will increase reader comprehension in a practical way while providing hands-on examples of performing the necessary tasks to create an XBRL report in the software.</div>
<p class="tdh_020"><span class="tdh_024">7.4.4     </span>The Transport Data Model</p>  

<div class="tdh_066">This section should describe the transport model in terms of how it can be used to structure the data necessary for XBRL reports. Preparers should now be aware of the types of data they need to gather to create the report, and they should know how it must be formatted and prepared to be transformed to XBRL. Authors can now explain the taxonomy and its constructs to help guide preparers in interacting with it as they transform their data into XBRL.</div>
<p class="tdh_026">7.4.4.1     Entry Points and Presentations</p>  

<div class="tdh_066">Authors should begin by describing the taxonomy&#8217;s entry points, particularly if these entry points are defined by pre-existing forms or use cases pertinent to XBRL report preparation. For example, if an entry point contains tables relevant to the information that once was reported via tabular format in human-readable form (such as a PDF or HTML document), this should be covered in detail. The particular presentations within the entry points should also be discussed as they are relevant to this topic. The goal of this section should be to orient readers who may be familiar with the pre-existing forms, documents, databases, and systems on how the XBRL taxonomy organizes that data.</div>
<div class="tdh_066">Authors can also explore the taxonomy&#8217;s presentations. Presentations should logically relate to the entry points and can be discussed in the context of the purpose of the entry point. The conversation can naturally progress to concepts and how XBRL uses them to represent the data and the dimensionality of the data.</div>
<p class="tdh_026">7.4.4.2     Concepts and How to Select Them</p>  

<div class="tdh_066">This section should address the concepts in the taxonomy and how they relate to common information in the field, industry, or business sector. Depending on the size and scope of the taxonomy, this discussion could be in-depth or cursory. The relationship the concepts have to the entry points, presentations, and the originating documents or databases should be explored as necessary. Authors should explain how some concepts are meant to be concept core dimensions (which directly relate to the fact and dictate the fact&#8217;s properties) and how other concepts are abstract and meant to group data. As with other sections of the <i>Preparer Guide,</i> authors should group content together to explain the most relevant information without redundant text.</div>
<div class="tdh_066">As possible, authors should also provide some guidance on how to select concepts to represent facts. In a sufficiently large taxonomy, preparers may feel overwhelmed by the number of concepts, so it may be helpful to explain any differences between similar concepts and provide general guidelines on how to choose concepts that are the most appropriate (examining concept labels, for example, to determine the best option). This may involve again linking the taxonomy to pre-existing forms, documents, and databases. If the taxonomy allows extensibility, authors should explore what that means and how it can be used by preparers to add custom concepts, should the concept with the appropriate meaning for a data point be unavailable to them. It may also be prudent to caution preparers about adding too many custom concepts and provide guidance on when it is best to create a concept versus using a pre-existing one.</div>
<p><!-- Field: Page; Sequence: 102 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->97<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_026">7.4.4.3     Data Types and Units</p>  

<div class="tdh_066">The <i>Preparer Guide</i> should include a listing of the kinds of standard data types used in the taxonomy (for example, string, monetary, Boolean, etc.). Authors may also discuss any non-standard or taxonomy-defined data types and how they should be used by preparers. The concepts (or types of concepts) that use these data types may be mentioned.</div>
<div class="tdh_066">Authors should also explore unit core dimensions, their usage, and where they are required. If the language core dimension is relevant to all or any part of the XBRL report, it should be covered here as well.</div>
<p class="tdh_026">7.4.4.4     Identifiers</p>  

<div class="tdh_066">Authors should discuss at length what types of identifiers are permissible in XBRL reports created using the taxonomy. Identifiers may be used with particular concepts (which may be constrained by the concept&#8217;s data type) or with an entity core dimension. Allowable identifiers vary from taxonomy to taxonomy. For example, XBRL reports concerning financial reporting may use Legal Entity Identifiers (LEIs) or other codes or identifiers associated with financial transactions. An XBRL report using a taxonomy designed to track widget production might employ identifiers specific to widget types. Guidance should be provided here as to which identifiers are allowed and the standards underlying them (such as ISO 17442 for LEIs, for instance).</div>
<p class="tdh_026">7.4.4.5     When and How to Use Taxonomy-defined Dimensions</p>  

<div class="tdh_066">It can be very daunting for both the novice and experienced XBRL user to determine how best to structure their data in an XBRL report. Creating dimensionality can be a difficult prospect, particularly in very complex data. Authors of the <i>Preparer Guide </i>should devote time in this section describing the dimensionality of the tables in the taxonomy and how those tables represent that data with which readers will be familiar. This will be key in the readers&#8217; understanding of how to translate their data as it currently is stored and formatted into XBRL, not mechanically but in terms of how the XBRL concepts and dimensions relate to the structure of their data model. Again, authors should present the most pertinent information and reduce redundancy by grouping similar tables together as much as possible.</div>
<p class="tdh_026">7.4.4.6     Calculations, Formulas, and Definitions (Optional)</p>  

<div class="tdh_066">All other relevant concept relationships should be discussed in this section. This should include, but may not be limited to, calculations, formulas, and definitions. As applicable, each type of relationship should be described, with authors taking care to explain the reasoning behind the relationship and how the taxonomy structure and linkbases define and support the relationship. If the concept relationship confers validation (such as concept A and concept B must sum through a calculation arc to concept C), this should also be covered.</div>
<p class="tdh_026">7.4.4.7     Labels and Footnotes</p>  

<div class="tdh_066">Concept labels should be covered in detail. Generally, industry standards will dictate what is appropriate to be used as a concept label. Preparers should be advised to use labels to aid in selection of concepts. Additionally, if the taxonomy allows extensible concepts, preparers should be provided with some guidance on how to select meaningful, relevant information for labels.</div>
<div class="tdh_066">In addition, as applicable, preparers should be guided on how to appropriately use footnotes and the note core dimension. Industry rules and accepted formats may dictate what sort of information can be represented as a footnote, and authors may wish to remind preparers of these standards or direct readers to where they can get more information.</div>
<p class="tdh_020"><a name="a_Ref20993045"></a><span class="tdh_024">7.4.5     </span>Extensibility</p>  

<div class="tdh_066">If the taxonomy is open, authors should include this important section to indicate to preparers how they may extend the taxonomy and under what conditions. For example, are preparers allowed to develop their own custom concepts should the exact concept they need not be available in the taxonomy? If so, what sort of supporting documentation and labels are required? Are preparers permitted to create their</div>
<p><!-- Field: Page; Sequence: 103 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->98<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">own taxonomy-defined dimensions to represent new dimensionality? Extensibility can also allow preparers to create their own presentations or even their own data types. Depending on the restrictions put in place by taxonomy developers, there may be a great deal of options for preparers to adjust the taxonomy to address their specific reporting needs.</div>
<div class="tdh_066">Because extensibility can reduce comparability and data integrity, authors should provide clear guidance on how and when to extend the taxonomy. This discussion should be tailored and specific to the ways in which the taxonomy can be extended (i.e., adding custom concepts or creating new presentations that group pre-existing concepts).</div>
<p class="tdh_020"><span class="tdh_024">7.4.6     </span>Transport Format and Instance Preparation</p>  

<div class="tdh_066">This topic is of particular importance to preparers. Given the taxonomy, what format must the XBRL report use? In this section, authors should provide very clear directions about creating the report. This should include an in-depth discussion of the transport format taxonomy developers have chosen, whether it is XBRL as XML, inline XBRL, JSON, or CSV. Alternatively, there may not be a requirement that the XBRL report be prepared in a specific type of format. This should be indicated in this section as well. The template provided in Appendix F contains boilerplate descriptions of each of these formats as related to XBRL.</div>
<div class="tdh_066">Any other considerations in creating XBRL instance documents with the taxonomy should be discussed. For example, if the reporting situation requires additional documents (such as cover pages or other expository information that isn&#8217;t tagged with XBRL), this should be explained. If there are regulatory and/or other requirements driving the reporting situation, authors may wish to explore how those requirements impact both the content and structure of the XBRL report. If reports are to be presented in Inline XBRL, for example, are preparers allowed to use images, hyperlinks, and other HTML elements to further explain or embellish their documents? Questions and issues such as these should be completely discussed so that preparers are very clear with what the report must contain and how that information must be presented.</div>
<p class="tdh_020"><span class="tdh_024">7.4.7     </span>Validation</p>  

<div class="tdh_066">Validating the data included in an XBRL report is an extremely important step in the creation and reporting process. Authors should stress that preparers should take care in validating the correctness of the information they are reporting, and tools should be provided to guide preparers through this process. As applicable, the next sections should be covered. Depending on third-party software availability and acceptance by taxonomy developers, authors may also wish to direct preparers to software solutions that implement data validation.</div>
<p class="tdh_026">7.4.7.1     Data Quality</p>  

<div class="tdh_066">Producing high quality data is a key goal in implementing a structured reporting taxonomy. Authors should indicate what defines high quality data for the industry or reporting situation (i.e., correctness of numeric information, what must be provided in textual sections, and precision and accuracy standards employed within the taxonomy). Quite often, taxonomy development and/or governance groups may have a data quality committee. If applicable, authors should explore what rules this committee has in place and how to follow them. If there are too many data quality rules or recommendations to discuss individually, authors should direct preparers to outside resources to aid them.</div>
<p class="tdh_026">7.4.7.2     Regulatory Requirements (Optional)</p>  

<div class="tdh_066">If meeting regulatory requirements are a major part of the taxonomy&#8217;s purpose, their influence on data quality and accuracy should be discussed here. In addition, authors should advise preparers on what sort of information may be necessary to meet some of those requirements. Again, if the requirements are too numerous or complicated to explain in this section, authors should indicate to readers where they can obtain more information.</div>
<p><!-- Field: Page; Sequence: 104 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->99<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_026">7.4.7.3     Using Data Types and Concept Relationships to Validate Facts</p>  

<div class="tdh_066">XBRL has constructs inherent to it that help validate data. Authors of the <i>Preparer Guide</i> should advise preparers of those protections, such as data types and concept relationships. The latter can be tied into the previous discussion of calculations, formulas, and definitions, but it should be mentioned here as a way to validate the data. Preparers should be reminded that XBRL only defines the relationships mathematically; it is up to the preparer or a software solution to check the values involved in the relationship for accuracy.</div>
<p class="tdh_020"><span class="tdh_024">7.4.8     </span>Supporting Systems (Optional)</p>  

<div class="tdh_066">In this section, authors may wish to describe what supporting systems, if any, exist to aid in the preparation and transmission of XBRL reports prepared with the taxonomy. This could include software (open source or not) that aids preparers in using the taxonomy and validating the data in their reports (which probably has been described in the <i>Preparer Guide </i>already). Of interest here are supporting transmission systems.</div>
<div class="tdh_066">The final part of preparing an XBRL report likely lies in sending that report to consumers. Depending on the reporting scenarios, this may be to an internal company or industry auditor, to a governmental or non-governmental regulator, or to the public. Quite commonly there will be a submission and/or dissemination system in place. Authors should describe what this system is and its components. If appropriate, a step-by-step guide to using the system can be supplied.</div>
<p class="tdh_020"><span class="tdh_024">7.4.9     </span>Examples</p>  

<div class="tdh_066">This content can be included as its own section or interlaced with other sections as appropriate. If the taxonomy is complex with many presentations and entry points, authors may wish to include in-depth examples of XBRL instance preparation. For example, the US GAAP financial reporting taxonomy has numerous examples that show the proper way of coding various complex notes to financials in XBRL. Authors may wish to present their examples as step-by-step guides using fictitious or publicly available data. Again, if there is provided or endorsed preparation software, tying the example to procedures within the software (with screenshots of dialogs or other images) can be particularly helpful to preparers.</div>
<p class="tdh_020"><span class="tdh_024">7.4.10     </span>Common Pitfalls and Troubleshooting</p>  

<div class="tdh_066">In this section, authors can cover some commonly encountered issues and how to overcome them. With any sufficiently complex process, there can be many steps that can pose challenges. In addition, preparers may make some obvious mistakes. For example, improperly scaling data in Inline XBRL so that the displayed information matches the correct values is a very common mistake. This part of the guide should describe how to avoid issues like these. The topics covered should be brief and instructional, and they should ideally be derived from real-world experience, feedback, and examples with the process of taking the current data in the field, formatting it as XBRL, validating it, and transmitting it.</div>
<p class="tdh_020"><span class="tdh_024">7.4.11     </span>References and Other Resources</p>  

<div class="tdh_066">In this concluding section, authors should explain what references were used in writing the <i>Preparer Guide</i>, which may include the taxonomy&#8217;s <i>Taxonomy Guide </i>(if it resides in a different document)<i>,</i> the current XBRL technical specifications, as well as industry specific resources and regulations that are relevant to XBRL report preparation. Authors should also include ways to contact the taxonomy developers and governance committees as applicable so that preparers can receive responses to comments, questions, and concerns.</div>
<div class="tdh_027"><a name="a_Toc24107567"></a><a name="a_Toc23337713"></a><a name="a_Toc15912860"></a><a name="a_Toc15912923"></a>7.5   The <i>Data Consumer Guide</i></div>
<div class="tdh_066"><a name="c7_data_consumer_guide"></a>The <i>Data Consumer Guide</i> presents common use cases for the data represented by the taxonomy. Oftentimes this document is part of the <i>Taxonomy Guide </i>itself, but it should be separated if it is long and complicated enough that the information is not applicable to both development and data consumer audiences.</div>
<p><!-- Field: Page; Sequence: 105 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->100<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_020"><span class="tdh_024">7.5.1     </span>Goals</p>  

<div class="tdh_066">This section clearly describes the overall goals of the <i>Data Consumer Guide</i> to the readers. Additionally, authors should describe the target audience of the <i>Data Consumer Guide </i>and may indicate the level of familiarity these readers should have with the data in question. For example, for a financial reporting taxonomy, the <i>Data Consumer Guide</i>&#8216;s target readers may be regulators, investment analysts, database providers, and other financial professionals who are familiar with US GAAP accounting standards.</div>
<p class="tdh_026">7.5.1.1     Revision History</p>  

<div class="tdh_066">Authors should mention that the document is subject to periodic revision in addition to describing its revision history. The governance process should be briefly described as it pertains to taxonomy and documentation updates so that readers are aware that changes can be made and how those changes will be implemented.</div>
<p class="tdh_020"><span class="tdh_024">7.5.2     </span>Why Use Cases Are Important</p>  

<div class="tdh_066">Authors should use this section to define use cases in broad terms and explain their utility in data analysis as well as their relationship with the taxonomy. A general description is provided in the <i>Data Consumer Guide </i>template in Appendix G. The types of use cases to be covered in the document can be briefly mentioned and outlined.</div>
<p class="tdh_020"><span class="tdh_024">7.5.3     </span>Introduction to the Taxonomy and an Overview of XBRL</p>  

<div class="tdh_066">Authors should begin by introducing the taxonomy and its purpose at a very high level. Readers should be aware of why the taxonomy exists, the types of data it is meant to represent, and its place along the information supply chain for the industry or business sectors for which it has been developed. Additionally, in the <i>Data Consumer Guide</i> there should be a brief description of the regulations and requirements that influenced how the taxonomy was designed to represent data. These regulations may not necessarily align with the use case in which the reader is interested, but they are important to understand the taxonomy&#8217;s purpose. <span class="tdh_001">The discussion can also feature a discussion and possibly a graphical representation of the data supply chain specific to this taxonomy.</span></div>
<div class="tdh_066">Authors should include the <i>XBRL Overview</i> (Appendix D), for which XBRL US has provided a pre-constructed template. This section should provide a basic primer on XBRL so that readers unfamiliar with the standard can quickly come up to speed with its basic constructs and usages.</div>
<p class="tdh_020"><span class="tdh_024">7.5.4     </span>Review of the Taxonomy</p>  

<div class="tdh_066">This section of the <i>Data Consumer Guide</i> provides a walkthrough of the structure and content of the taxonomy.</div>
<p class="tdh_026">7.5.4.1     Taxonomy Physical Structure</p>  

<div class="tdh_066">With the transport data model understood by readers, this section can articulate how the taxonomy represents that model. Because this topic is so important, authors should take care to ensure their explanations of the rationales behind the taxonomy&#8217;s design choices are clear.</div>
<div class="tdh_066">Using both diagrams and text, the section should describe the structure of the taxonomy in detail, including presentations and entry points. Authors may describe why these groupings were created, what they are designed to capture, and who is the target audience for the various entry points and presentations. This information may be of great interest to data consumers, particularly if the presentations and entry points are designed to group data relevant to certain use cases.</div>
<div class="tdh_066">As with most aspects of documentation, the size and scope of the taxonomy should dictate the level of detail and explanation required to ensure understanding. Large taxonomies, such as the Orange Button Taxonomy which has over 4,000 concepts, may need to be explained by grouping content into logical &#8220;sections&#8221; and providing an in-depth review of each section. Logical sections may be entry points, presentations, tables, or even abstract concepts if this grouping is complex enough to merit further detail. Smaller taxonomies, such as the Surety Work In Process Taxonomy which has approximately 60</div>
<p><!-- Field: Page; Sequence: 106 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->101<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">concepts, may be handled differently. In a smaller taxonomy, authors can spend more time on detailed descriptions of each category of data, describing the meaning of the concepts and how they work within the limited number of tables.</div>
<p class="tdh_026">7.5.4.2     Concepts</p>  

<div class="tdh_066">This section should address the concepts in the taxonomy and how they relate to common information in the field, industry, or business sector. Depending on the size and scope of the taxonomy, this discussion could be in-depth or cursory. The relationship the concepts have to the entry points, presentations, and the originating documents or databases should be explored as necessary. Authors should explain how some concepts are meant to be concept core dimensions (which directly relate to the fact and dictate the fact&#8217;s properties) and how other concepts are abstract and meant to group and dimensionalize data. As with other sections of the <i>Data Consumer Guide,</i> authors should group content together to explain the most relevant information without redundant text.</div>
<p class="tdh_026">7.5.4.3     Dimensions</p>  

<div class="tdh_066">The dimensionality of tables within each section of the taxonomy should be described in detail, including core dimensions (allowable units, entities, etc.) and how to use the taxonomy-defined dimensions that comprise the table. Understanding the dimensionality of the data within the taxonomy is important when translating the taxonomy&#8217;s transport model to data consumption models. How do the taxonomy-defined dimensions relate to data dimensions in the use case? How do the concept core dimensions match data points in the consumption model? Clearly these relationships are essential in usefully interpreting the taxonomy.</div>
<div class="tdh_066">Again, the size of this section depends on the complexity and scope of the taxonomy. For a very large taxonomy, if many of the tables contain similar dimensional structures, an exemplar table can be explained in greater detail to illustrate the structure with a briefer discussion as to how this structure applies elsewhere. Tables can also be grouped in the discussion if they represent similar data and dimensionality. The goal is, as always, explaining the relevant information with as little duplicative or redundant material as possible.</div>
<p class="tdh_026">7.5.4.4     Calculations (Optional)</p>  

<div class="tdh_066">If the taxonomy contains calculations, this section should include a brief explanation of the calculation relationships between concepts.</div>
<p class="tdh_026">7.5.4.5     Formulas (Optional)</p>  

<div class="tdh_066">If the taxonomy contains formulas, this section should include a brief explanation of the formula relationships between concepts.</div>
<p class="tdh_026">7.5.4.6     Data Types and Units</p>  

<div class="tdh_066">The <i>Data Consumer Guide</i> should include a listing of the kinds of standard data types used (for example, string, monetary, Boolean, etc.) and any non-standard or custom data types. Non-standard and custom data types are particularly important to describe, since these are not likely to be included automatically in a data consumption model or analysis software.</div>
<div class="tdh_066">Authors should also discuss unit core dimensions and the mathematical, scientific, or financial context they confer to the data.</div>
<p class="tdh_026">7.5.4.7     Validation and Measuring Data Integrity</p>  

<div class="tdh_066">Validation rules and procedures give an opportunity for the consumer to have a higher level of confidence in the incoming data. If standard validation models have been developed for the taxonomy, authors should discuss them here.</div>
<p><!-- Field: Page; Sequence: 107 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->102<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_020"><span class="tdh_024">7.5.5     </span>Extracting Data from an XBRL Report</p>  

<div class="tdh_066">Authors can use this section to explore the mechanics of gathering data from an XBRL report, which consumers must do in order to analyze and interpret that data in their use cases. As applicable, authors may wish to describe methods for extracting the information from instance documents. This may involve third-party or proprietary software packages that may be custom built to transfer data from XBRL documents into analysis systems.</div>
<p class="tdh_026">7.5.5.1     Transport Format</p>  

<div class="tdh_066">In this section, authors should provide a description of what transport format data consumers will find XBRL reports using, whether it be XBRL as XML, inline XBRL, JSON, or CSV. The template provided in Appendix G contains boilerplate descriptions of each of these formats as related to XBRL.</div>
<p class="tdh_026">7.5.5.2     Data Software Tools and Other Supporting Systems</p>  

<div class="tdh_066">In this section, authors should describe where the XBRL reports generated with the taxonomy will be stored and how they can be accessed. For example, will the information be publicly available? If not, what sort of credentials will be necessary to access it? Will multiple XBRL reports be stored in a single repository, and how can that information be obtained? How is information organized by reporting entity and reporting period?</div>
<div class="tdh_066">Authors should also discuss any software tools and systems that can aid consumers in extracting and analyzing XBRL data. These systems may be proprietary or available through third-party software vendors. If a software solution is not specifically endorsed by the taxonomy developers and/or governance groups, authors should take care in discussing it.</div>
<div class="tdh_066">In particular, authors may wish to cover the XBRL API, which is freely available from XBRL US. As briefly discussed in Section 1.4.2, the XBRL API offers a programming interface that can connect a database backend with a data gathering/analysis frontend (such as a web interface) to allow users to build their own databases with XBRL information from a repository. Data consumers can be advised that they can use this API to create their own XBRL data gathering system, if one does not currently exist.</div>
<p class="tdh_020"><span class="tdh_024">7.5.6     </span>Common Use Cases</p>  

<div class="tdh_066">This should comprise the bulk of the <i>Data Consumer Guide</i>, and the content will vary widely depending on the taxonomy and industry itself. Authors will want to create separate sections for each use case they wish to describe. Obviously, this list of use cases cannot be exhaustive; authors must decide which use cases are the most common and/or most important for consumers to understand in detail.</div>
<div class="tdh_066">For each use case, authors may wish to begin by outlining the goal of the use case. Example use case goals may be to compare widget production among competing companies or to generate aggregate data on mining company assets across the mining industry. Whatever the goal of the use case, authors should describe it in detail. After, authors should indicate how the taxonomy represents data relevant to that goal. For some use cases, particularly those the taxonomy may have been designed to support, this discussion may be lengthy, as a great deal of the data (and therefore the taxonomy) may be involved in the use case. For others, the situation may be simpler and confined to a single entry point, presentation, or table.</div>
<div class="tdh_066">Regardless of the scope of the discussion, authors should explain how the concepts and taxonomy-defined dimensions map onto the data necessary for the use case. Using the widget example again, if the use case involves monitoring widget production for a specific quarter, the guide may indicate which concepts and dimensions are necessary to extract that data from the taxonomy. More complex use cases may require significant discussion so that readers understand this key step.</div>
<p class="tdh_020"><span class="tdh_024">7.5.7     </span>Special Considerations and Extensibility (Optional)</p>  

<div class="tdh_066">If there are any special considerations concerning gathering the data from the taxonomy, those should also be discussed as relevant to each use case. For example, if the taxonomy allows extensibility, there may be custom concepts, dimensions, and data types involved in the XBRL reports, and these may vary</div>
<p><!-- Field: Page; Sequence: 108 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->103<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">from preparer to preparer. Authors may wish to provide guidance to consumers on how to handle these situations.</div>
<div class="tdh_066">If there is extensibility, it can significantly impact the abilities of consumers to model the data.</div>
<p class="tdh_020"><span class="tdh_024">7.5.8     </span>References and Other Resources</p>  

<div class="tdh_066">In this concluding section, authors should explain what references were used in writing the <i>Data Consumer Guide</i>, which may include the taxonomy&#8217;s <i>Taxonomy Guide </i>(if it resides in a different document)<i>,</i> the current XBRL technical specifications, as well as industry specific resources and regulations that are relevant to XBRL report preparation. Authors should also include ways to contact the taxonomy developers and governance committees as applicable so that data consumers can receive responses to comments, questions, and concerns.</div>
<div class="tdh_027"><a name="a_Toc24107568"></a><a name="a_Toc23337714"></a>7.6   Updates and Release Notes</div>
<div class="tdh_066">When the taxonomy is released and then subsequently updated, information about the changes should be documented and disseminated through revision and release notes. Release notes are generally concise and written for a technical audience. For the initial release, these notes may outline the general purpose and structure of the taxonomy, potentially sending readers to the <i>Taxonomy Guide </i>or other XBRL specifications as necessary. For revisions thereafter, the release notes should completely cover the change (which may be an addition, alteration, or a deletion of taxonomy constructs or a new interpretation of taxonomy elements), potentially explaining the reasoning behind the change and advising users of other relevant considerations if necessary. If the change is driven by new or different regulations or by modifications from another governing body, the release notes should directly cite the reason for each change.</div>
<div class="tdh_066">Any beta or pre-releases of the taxonomy should also contain release notes. More information on how to structure and release changes to a taxonomy can be found in Chapter 8.</div>
<p><!-- Field: Page; Sequence: 109 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->104<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt; float: right; margin: 8px; border: 1px solid #e2e2e2; border-bottom: none;"><a href="#toc">Table of Contents</a></div>
<div class="tdh_028"><a name="a_Toc24107569"></a><a name="a_Toc23337715"></a><a name="a_Ref11916912"></a><a name="a_Ref11750358"></a>8   Taxonomy Governance</div>
<div class="tdh_066"><a name="c8_governance"></a>As with any project, the lifecycle and workflow of a taxonomy will naturally include development, deployment, and eventually revision and support. These later aspects of the lifecycle are sometimes less investigated or emphasized, but they can be vitally important to the success of any project, an XBRL taxonomy included. This chapter offers some methods of oversight and management to guide the entire process of taxonomy development, implementation, and upkeep. These are only suggestions; developers and other managers should create and install a management structure that makes sense to them.</div>
<div class="tdh_066"><i>Taxonomy governance</i> is comprised of the policies, processes, and documentation needed to manage and use taxonomies, not only in the initial building stage but throughout ongoing support and maintenance. A taxonomy is seldom &#8220;finished&#8221; because regulatory reporting requirements, industry and company needs, and marketplace technologies continuously change. The taxonomy must evolve to meet the needs of the reporting domain and to embrace new technologies that can offer enhancements to the information supply chain.</div>
<div class="tdh_066">The overarching goal of taxonomy governance is to establish a repeatable, predictable process to manage taxonomy changes in a manner that is accountable and transparent to all stakeholders. This chapter briefly outlines the development cycle for a taxonomy. It also describes the team of personnel that could be involved in governance tasks, as well as their roles and responsibilities. It bears mentioning again that the size and scope of governance and the groups involved in it should be dictated by the size and scope of the taxonomy itself. For a large, complex taxonomy with multiple regulatory stakeholders, governance may require many different people with different expertise. For a small taxonomy with a more contained information supply chain, the taxonomy developers themselves may be all that is necessary to maintain robust governance.</div>
<div class="tdh_027"><a name="a_Toc24107570"></a><a name="a_Toc23337716"></a>8.1   The Taxonomy Lifecycle</div>
<div class="tdh_066"><a name="c8_taxonomy_lifecycle"></a>Like most structured systems, taxonomies have a general lifecycle: build, implementation, and support and maintenance. The governance structure and goals should adapt to the stage of taxonomy development and maintenance (Figure 8-1.).</div>
<p class="tdh_099"><a href="https://www.draw.io/#G1AJlIRDX4x29xKPzj_-HhURQ7IZucW2LR"><img class="tdh_152" src="http://files.xbrl.us/images/tdh/tdh_p1_048.jpg" alt="" /></a></p>  

<p class="tdh_106"><a name="a_Ref22123421"></a>Figure 8-1. The lifecycle of taxonomy development and governance</p>  

<div class="tdh_066">Note that these phases correspond with the development workflow diagram depicted in Figure 6-1. The development and revision cycles in that diagram match the phases listed in this chapter. The following sections outline the goals of each phase and types of governance structures necessary to achieve them.</div>
<p><!-- Field: Page; Sequence: 110 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->105<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_020"><span class="tdh_024">8.1.1     </span>Phase 1 — Build</p>  

<div class="tdh_066"><a name="c8_build_phase"></a>Most of this handbook has thus far focused on the <i>build phase</i>, which obviously focuses on defining the project goals, the requirements of the taxonomy, constructing and validating the XBRL data transport model, and documenting the results. The goal of the build phase is to produce a <i>pilot taxonomy</i> for public review. During this initial build of the taxonomy, the governance should provide oversight to the defining of roles, documenting of the taxonomy, report preparation, and use cases, marketing the practicality and value of the taxonomy to those involved in the industry or information supply chain, and identifying of success metrics. The types of governing bodies and personnel that are typically involved are outlined below.</div>
<p class="tdh_026">8.1.1.1     The Sponsor</p>  

<div class="tdh_066">The <i>taxonomy sponsor</i> champions the development project. For large taxonomies with wide impact on the information supply chain, a regulator, standards organization, or non-profit industry body may act as sponsor to successfully bring together stakeholders. In these cases, commercial entities typically do not take on this role because their own financial or business interests may conflict with the needs of other stakeholders and may cause roadblocks to competitive collaboration. However, a group of companies with a common interest could come together in an alliance and act as sponsor.</div>
<div class="tdh_066">In smaller, more contained reporting situations, the taxonomy sponsor may be within the management structure of a company. Again, the size of the project dictates the level of oversight necessary.</div>
<p class="tdh_026">8.1.1.2     The Working Group</p>  

<div class="tdh_066">All stakeholders should be represented in the <i>taxonomy working group</i>. This may include preparers, data intermediaries, and data consumers, as well as software and database providers. Developers themselves should also be a part of this group. Collaborating with technical and subject matter experts, they will be called upon to perform the tasks to develop the taxonomy deliverables. Regulators, legislators, and industry experts can serve as observers to ensure legislative requirements and regulatory goals are correctly implemented. Even in small settings, the working group will likely comprise more than one person, and collaboration among all parties necessary to design, develop, and deliver the taxonomy is essential.</div>
<div class="tdh_066">As practical, working group members can work independently on sections of the taxonomy, but the full taxonomy working group should convene periodically to evaluate development progress and to report to overseeing bodies, including the steering committee.</div>
<p class="tdh_026">8.1.1.3     The Taxonomy Steering Committee</p>  

<div class="tdh_066">Usually led by the sponsor, a <i>taxonomy steering committee</i> evaluates major milestones, reviews and approves deliverables, and serves as &#8220;tie breaker&#8221; on major decisions concerning the taxonomy. This is the body providing the main oversight to the development process. The taxonomy steering committee can typically meet less frequently. Like the working group, it should be comprised of technical and subject matter experts who represent the various stakeholders to the project.</div>
<div class="tdh_066">In small reporting situations, a taxonomy steering committee may not be necessary or redundant.</div>
<p class="tdh_026">8.1.1.4     Taxonomy Manager</p>  

<div class="tdh_066">The <i>taxonomy manager</i> maintains detailed knowledge of the taxonomy and the project as a whole and provides day-to-day staff support for the taxonomy working group. The taxonomy manager also receives, reviews, and triages submitted comments and change requests, assesses the impact of these requests, and reports back to the taxonomy working group. This individual also coordinates with regulators, industry organizations, and data quality experts, if they are involved.</div>
<div class="tdh_066">In addition to these responsibilities, the taxonomy manager acknowledges the receipt of all comments to the submitters and maintains and publishes all records related to change requests. This person also implements and tests approved changes, conducts version testing and publication, coordinates approval for all proposed changes, and oversees all tasks involved.</div>
<p><!-- Field: Page; Sequence: 111 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->106<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_026">8.1.1.5     Considerations</p>  

<div class="tdh_066">Questions that should be considered by the working group and steering committee during the development phase are:</div>
<ul>
<li><span class="tdh_190">Who are the taxonomy stakeholders?</span></li>
<li><span class="tdh_190">What is the scope of the taxonomy?</span></li>
<li><span class="tdh_190">When is it &#8220;pencils down&#8221;? At some point, the taxonomy needs to be considered a pilot/candidate taxonomy. Should more changes be made, or should these changes be held for a subsequent release?</span></li>
<li><span class="tdh_190">What is the metric of success?</span></li>
<li><span class="tdh_190">What are the best vehicles (email, webinars, in-person meetings, training classes, etc.) to communicate and reach the appropriate audience?</span></li>
<li><span class="tdh_190">Have software providers been able to incorporate the taxonomy successfully into their applications? What additional tools (such as sample instance documents and documentation on the architecture of the taxonomy) might they need?</span></li>
</ul>
<div class="tdh_066">Many of these topics are discussed in greater detail in Chapters 4 and 5.</div>
<p class="tdh_020"><span class="tdh_024">8.1.2     </span>Phase 2 — Pilot</p>  

<div class="tdh_066"><a name="c8_pilot_phase"></a>After the taxonomy has been developed, it enters into a <i>pilot phase</i>. During this phase, the pilot taxonomy (or candidate taxonomy, if this is review is part of a revision cycle; see Figure 6-1) must be tested extensively in various internal and external revision cycles. The taxonomy working group and steering committee should first ensure the taxonomy meets its requirements, both functional and non-functional. If there are regulatory constraints, they must also be evaluated. This may involve input from regulators themselves or other stakeholders defining the regulatory rules. At this earliest testing stage, it is extremely important that the metric of success as pertinent to the taxonomy&#8217;s developmental requirements is refined and applied to determine whether or not the taxonomy succeeds.</div>
<div class="tdh_066">In addition, the taxonomy steering committee and working group should oversee additional testing cycles to examine the integrity of the taxonomy. This includes the testing taxonomy&#8217;s structure, concepts, and concept relationships to make sure they are correct. All aspects of the taxonomy, including how well the transport format serves in instance documents, should be evaluated. The working group should ensure developers, testers, and quality assurance personnel have the necessary tools (software, sample documents and data sets) to complete this testing. Internal revisions should be documented and overseen by the taxonomy manager.</div>
<div class="tdh_066">At this point, another governance group, the <i>data quality committee</i>, may become necessary. This group, likely comprised of data and industry experts, oversees establishing data quality rules for the taxonomy. In collaboration with the taxonomy working group, data integrity benchmarks should be developed. They can be a mixture of regulatory compliance rules and particular precepts for accurate data, depending on the taxonomy. These rules are typically layered on top of XBRL&#8217;s inherent validation. Care should be taken to incorporate data quality rules in both documentation and supporting systems and software. Note that a separate data quality committee may not be necessary</div>
<div class="tdh_066">Once this internal testing period is over and the pilot taxonomy has its major problems and shortcomings resolved, the candidate/pilot taxonomy can be released for <i>public review</i>. Again, the breadth of &#8220;public&#8221; varies widely depending on the size and scope of the taxonomy itself and the information supply chain. The length of the review period should also be dictated by the need for public comment. External exposure is an important step, first, to ensure that the taxonomy truly meets the needs of the stakeholders it serves, and, second, to ramp up the adoption effort. These two goals typically go hand in hand for a large reporting landscape.</div>
<div class="tdh_066">This will be the first opportunity many taxonomy users will be able to evaluate, study, test, and &#8220;play around&#8221; with the taxonomy. Despite all best efforts, it is very unlikely, particularly if the taxonomy is large and is designed to cover multiple use cases, that it will be a perfect fit for all stakeholders and applications. There may also be lingering &#8220;bugs&#8221; in the taxonomy that were not caught during the first</div>
<p><!-- Field: Page; Sequence: 112 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->107<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">rounds of review, such as inconsistency of labels or even typos. It is important to have a process in place to capture needed additions and revisions to the taxonomy, as well as mistakes, as individuals begin using it.</div>
<div class="tdh_066">After the public review, the comments received should be evaluated by the taxonomy manager. Corrections (version and source tracking software are recommended) can be incorporated. Once the taxonomy working group and steering committee are satisfied the necessary changes have been implemented and validated, the candidate taxonomy becomes a <i>draft taxonomy</i> and can move to the next stage of its lifecycle: implementation.</div>
<p class="tdh_026">8.1.2.1     Considerations</p>  

<div class="tdh_066">The following should be considered by the governance parties during the pilot phase:</div>
<ul>
<li><span class="tdh_190">Does the taxonomy accomplish its goals and meet its requirements?</span></li>
<li><span class="tdh_190">Has the metric of success been properly applied? If so, is the taxonomy succeeding as indicated by this rubric?</span></li>
<li><span class="tdh_190">Who will decide if a proposed change (from internal or public review) is necessary and/or practical?</span></li>
<li><span class="tdh_190">How does a proposed change affect each information chain member?</span></li>
<li><span class="tdh_190">How does a proposed change affect the rest of the taxonomy?</span></li>
<li><span class="tdh_190">How should a public review be conducted and communicated?</span></li>
<li><span class="tdh_190">How should changes from the public review period be handled?</span></li>
<li><span class="tdh_190">How can taxonomy working group members track and manage changes in an effective, coordinated way?</span></li>
</ul>
<p class="tdh_020"><span class="tdh_024">8.1.3     </span>Phase 3 — Implementation</p>  

<div class="tdh_066"><a name="c8_implementation_phase"></a>Once the review (public or internal as appropriate) is complete, all appropriate changes are incorporated, and the initial release is published, the draft taxonomy moves into <i>implementation</i> phase and becomes a formally <i>released taxonomy</i>.</div>
<div class="tdh_066">As the bulk of design, development, and testing is at this point complete, the taxonomy working group and taxonomy steering committee can be consolidated and streamlined into a <i>taxonomy committee</i>. This committee can begin to focus on the long-term success of the taxonomy. Accordingly, much of the governance in the implementation phase concerns ensuring the deployment is smooth and support for adopters is available. A deployment schedule should be determined early in the implementation phase. This schedule should anticipate the needs of the reporting community and deliver resources in a logical way. If supporting software is necessary and in development but not yet ready, can users access the taxonomy without it? Conversely, should the taxonomy release be delayed until the software and taxonomy can be released as a package?</div>
<div class="tdh_066">The implementation phase also provides an opportunity to continue to evaluate the system in its entirety: the taxonomy, supporting software and systems, documentation, and education. Expectations from the reporting community should be addressed as part of the adoption and education initiatives. Even the most robust testing regimen cannot anticipate all difficulties, particularly when a deployment is large and complex with multiple types of users interacting with a system. The governance structure should be prepared to adapt quickly to emergency situations. If appropriate, the governance bodies, in particular the taxonomy manager, may wish to develop easy ways to adopters (particularly preparers) to interact with useful documentation and technical support, as well as continue to allow these users to provide feedback. Actively soliciting input from early adopters helps ensure that they remain positively engaged in working with the developers and improving on the taxonomy.</div>
<div class="tdh_066">Also, adoption is not an &#8220;all-or-none&#8221; concept. Governance committees must factor in a level of acceptable adoption in the metric of success. In some reporting situations, adoption may not be optional. In others, particularly with large taxonomies that impact many preparers, a staggered method of adoption may be of benefit.</div>
<p><!-- Field: Page; Sequence: 113 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->108<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_026">8.1.3.1     Considerations</p>  

<div class="tdh_066">Questions that should be considered by the taxonomy manager and committee during the implementation phase include:</div>
<ul>
<li><span class="tdh_190">How can the taxonomy be released in a coordinated, well-structured manner? What are the mechanics of this process?</span></li>
<li><span class="tdh_190">Is supporting software necessary and available? If it is not ready, should the taxonomy release schedule coincide with its release? What is the best release schedule to reduce preparer frustration yet allow access to the taxonomy?</span></li>
<li><span class="tdh_190">Is there a system in place to disseminate news about the taxonomy&#8217;s release if necessary?</span></li>
<li><span class="tdh_190">Is proper education and training taking place for each stakeholder group?</span></li>
<li><span class="tdh_190">Is documentation ready and available? How can users access it?</span></li>
<li><span class="tdh_190">Is there more that can be done to encourage adoption and support users?</span></li>
</ul>
<p class="tdh_020"><span class="tdh_024">8.1.4     </span>Phase 3 — Support and Maintenance</p>  

<div class="tdh_066"><a name="c8_support_phase"></a>Once the taxonomy has been adopted, a comprehensive support and maintenance program needs to be established. The goal of this <i>support and maintenance</i> phase is to establish a long-term support cycle (Figure 6-1), which involves a vehicle to receive and react to requested and required changes, determine categories of change (high versus low impact, and who has authority for different types of changes), and create a revision implementation process (initial candidate taxonomy revised to a draft taxonomy and then released as a final taxonomy). Care should be taken to minimize the number of new releases and ensure they are either substantial or important as each one may require software providers to make adjustments every time a new version is published. The taxonomy committee should establish a process to revising and releasing taxonomy updates, including how those revisions will be announced, implemented, and tested.</div>
<div class="tdh_066">When evaluating changes, it is important for the taxonomy committee to consider their necessity and impact. Naturally, if the taxonomy includes regulatory requirements, changes to requirements will necessitate commensurate alterations to the taxonomy. Otherwise, the taxonomy committee should weigh the gain versus burden of each change. Some changes, such as correcting concept labels or restructuring relationships, may not require much implementation. Others can have more serious repercussions. Changes that will have the biggest impact and may affect instance documents that have already been prepared include:</div>
<ul>
<li><span class="tdh_190">Changing element names</span></li>
<li><span class="tdh_190">Structural changes, such as adding or removing tables</span></li>
<li><span class="tdh_190">Altering or adding data types</span></li>
<li><span class="tdh_190">Limiting or expanding extensibility</span></li>
<li><span class="tdh_190">Switching to, adding, or removing transport formats</span></li>
<li><span class="tdh_190">Changing concept names</span></li>
</ul>
<div class="tdh_066">One of the biggest advantages of XBRL is its extensibility. This allows the taxonomy to evolve with changing reporting requirements and environments. The taxonomy committee can periodically evaluate the goals of the taxonomy against the current reporting standards for the industry and those of similar industries. There may be improvements that can be made. Should substantial development work be necessary, the taxonomy committee can reform a working group to explore and potentially create new reporting solutions.</div>
<p class="tdh_026">8.1.4.1     Considerations</p>  

<div class="tdh_066">These considerations should be periodically considered by the taxonomy during the support and maintenance period.</div>
<ul>
<li><span class="tdh_190">What use cases may not be adequately covered? As the taxonomy matures and reporting requirements change, are elements missing? Are tables as they currently structured difficult to work with? Are there other &#8220;quality of life&#8221; improvements that may be made?</span></li>
</ul>
<p><!-- Field: Page; Sequence: 114 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->109<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<ul>
<li><span class="tdh_190">Were there topics that were held back in the earlier releases that can be incorporated in the future?</span></li>
<li><span class="tdh_190">Who makes the decision about whether a change should be made?</span></li>
<li><span class="tdh_190">Who is responsible for making changes?</span></li>
<li><span class="tdh_190">What is the process for making changes?</span></li>
<li><span class="tdh_190">How are prospective changes evaluated and prioritized?</span></li>
<li><span class="tdh_190">How often should releases be made? Should a public review of the draft, candidate taxonomy accompany each iteration?</span></li>
<li><span class="tdh_190">How should changes be communicated to the users?</span></li>
<li><span class="tdh_190">Are validation rules, if available, working appropriately to identify and resolve errors?<a name="a_zeviwizctpt1"></a><a name="a_t3scvjq6pht8"></a><a name="a_66zpwatdxvww"></a></span></li>
</ul>
<div class="tdh_027"><a name="a_Toc24107571"></a><a name="a_Toc23337717"></a>8.2   Effective Communication</div>
<div class="tdh_066">Successful governance requires effective communication to the development team, technical and subject matter experts, and to stakeholders all through the information supply chain. Some recommendations to ensure good communication include:</div>
<ul>
<li><span class="tdh_190">Know the audience. Tailor messaging to the various audiences (software providers, accounting professionals, investors) to get and keep them engaged.</span></li>
<li><span class="tdh_190">Avoid technical jargon. Adoption may rely on preparers and consumers that may not be experts in XBRL or even know what it is or why it is a good solution. Over-use of technical terms may make adoption seem burdensome and complicated. For more information on how to present the evidence that an XBRL taxonomy presents a strong solution to a reporting problem, see Section 7.2.</span></li>
<li><span class="tdh_190">Respond to feedback received. It is important to take advantage of all input received. Not only will it help improve the performance of the taxonomy, but by responding to the feedback and ensuring that commenters know their voice is heard, the path to adoption will be smoother.</span></li>
<li><span class="tdh_190">Document all comments received.</span></li>
<li><span class="tdh_190">Ensure all comments received are freely given, as applicable.</span></li>
<li><span class="tdh_190">Allow comments to be viewed by others.</span></li>
<li><span class="tdh_190">Allow viewers to comment on other comments.</span></li>
<li><span class="tdh_190">Publish release notes with new releases explaining the outcome of input received to help commenters see how their input is being put to use.<a name="a_Toc274342"></a><a name="a_Toc276620"></a><a name="a_Toc1560968"></a></span></li>
<li><span class="tdh_190">Provide robust documentation that can be used as a resource for taxonomy users to understand clearly what the taxonomy can do, why it has been designed as it has, and why it is important.</span></li>
</ul>
<p><!-- Field: Page; Sequence: 115 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->110<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt; float: right; margin: 8px; border: 1px solid #e2e2e2; border-bottom: none;"><a href="#toc">Table of Contents</a></div>
<div class="tdh_028"><a name="a_Toc24107572"></a><a name="a_Toc23337718"></a>9   Success Stories</div>
<div class="tdh_066">The XBRL data standard has been effectively implemented around the world, resulting in cost savings, greater accountability, and increased efficiency. Below are a handful of brief case studies to demonstrate these successes.</div>
<div class="tdh_027"><a name="a_Toc24107573"></a><a name="a_Toc23337719"></a>9.1   Banking in the United States</div>
<div class="tdh_066">The Federal Financial Institutions Examination Council (FFIEC) coordinates regulatory activities for the United States Federal Reserve, the Federal Insurance Deposit Commission (FDIC), and the Office of Thrift Supervision. Bank institutions are required to report financial information to the FFIEC on standardized forms called &#8220;call reports&#8221;. Call reports, which must be filed no later than thirty days after the end of the quarter, contain important financial data, including the bank&#8217;s income statement, balance sheet, information on loans, deposits, and investments, changes in the bank&#8217;s capital, and asset sale information. The reports are examined by federal analysts for errors and any other audit-related issues. <span class="tdh_022">Call report data is a critical source of information about the U.S. banking industry and is used by bank regulatory agencies to monitor banking activities. It is also used by the public, U.S. Congress, state banking authorities, researchers, rating agencies, investors, and academia. The FDIC is responsible for maintaining an accurate and up-to-date call reports database. </span></div>
<div class="tdh_066">Call reports, as shown in Figure 9-1, are highly structured, with required data well defined. Since 1998, banks have had to submit call report data electronically to the FFIEC Call Agencies. All banks are required to purchase one of nine approved vendor software packages to prepare their call report data.</div>
<p class="tdh_099"><img class="tdh_164" src="http://files.xbrl.us/images/tdh/tdh_p1_049.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref23244562"></a>Figure 9-1. An example of bank call data in table format</p>  

<p class="tdh_020"><span class="tdh_024">9.1.1     </span>Before Data Standards: Legacy System</p>  

<div class="tdh_066">Before call report was standardized, instructions and technical requirements on how to prepare the call report were distributed through a collection of PDF, Microsoft Word, and Microsoft Excel documents.</div>
<p><!-- Field: Page; Sequence: 116 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->111<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Manual manipulation by the software vendors and financial institutions was necessary to use the requirements information provided.</div>
<div class="tdh_066">A private sector vendor collected the data and made it available to the FFIEC agencies to process. The Federal Reserve System and the FDIC each reviewed and performed validation checks to test for mathematical and quality errors. Exceptions were resolved by FFIEC staff through contacting bank respondents by phone and manually entering corrections. In some cases, banks were required to correct and resubmit the data.</div>
<div class="tdh_066">The legacy process was not flexible or scalable, involved the use of multiple file formats, required manual preparation and validation, and was labor intensive, error-prone, and time-consuming. Enhancements to the system and changes to reporting requirements were also completed piecemeal, creating a system that would benefit from structured reporting.</div>
<p class="tdh_020"><span class="tdh_024">9.1.2     </span>Incorporating Data Standards</p>  

<div class="tdh_066">Banking regulators leveraged certain factors from the legacy systems to build the new, modernized system. First, these regulators worked closely with existing call report software vendors to revise their applications to generate standardized call report data. Because of the structured nature of standardized data, they were able to incorporate error and data quality checks into the software so that banks could edit and have confidence in their data prior to submission. Validation improved the timeliness and quality of the reports and reduced the need for manual vetting on the part of bank staff.</div>
<div class="tdh_066">Second, because of the highly structured, &#8220;forms-based&#8221; nature of the data reported, the regulators could implement a closed taxonomy that allowed no extensions. Finally, call report preparation software vendors were already a critical part of the reporting process, so naturally working with these vendors during the taxonomy development process during a series of roundtable discussions (led by bank regulators) was important in building a data reporting and collection process that would work for all stakeholders: regulators, software vendors, preparers, and data consumers. Preparers used the same software applications they had always used as the interface through which they accessed the taxonomy to determine what information to report and fill in. This meant that there was no significant learning curve for preparers; they were simply replicating an existing process. Thus, there was no disruption in the process for the thousands of banks that are required to submit call reports.</div>
<p class="tdh_020"><span class="tdh_024">9.1.3     </span>Results</p>  

<div class="tdh_066">The following results came up implementing XBRL as a standard in US bank financial reporting:</div>
<ul>
<li><span class="tdh_190">Cleaner data. 95% of banks&#8217; original filings met validation requirements after the XBRL taxonomy was implemented, as compared to 66% in the legacy system. </span></li>
<li><span class="tdh_190">More accurate. 100% of reported data met mathematical requirements under the new taxonomy (e.g., correct summations), as compared to 30%.</span></li>
<li><span class="tdh_190">Faster data inflow. Data was received into the system less than one day after the end of the reporting period, versus weeks after.</span></li>
<li><span class="tdh_190">Greater analyst efficiency. Analysts could handle 550 to 600 banks, versus 450 to 500.</span></li>
<li><span class="tdh_190">Faster data access. Analysts could access data within one day versus several days.</span></li>
<li><span class="tdh_190">Seamless throughput. Regulators and call report software vendors use the same taxonomies, so preparers are using the same requirements as the agencies.</span></li>
</ul>
<p class="tdh_020"><span class="tdh_024">9.1.4     </span>Conclusions</p>  

<div class="tdh_066">The success story of XBRL in bank financial reporting represents a situation where the current reporting regime heavily influenced XBRL taxonomy development and implementation. Because software vendors were already involved in the reporting process, involving them during development produced a valuable outcome for preparers: being able to continue to use the front-end of existing systems to develop reports without having to learn the intricacies of the new back-end (XBRL). In addition, involving developers this way allows them to fully understand and implement the taxonomy as appropriate. Further, the extensibility of the taxonomy must clearly be limited; the rigid reporting environment dictates this design</div>
<p><!-- Field: Page; Sequence: 117 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->112<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">choice. The structure of the data provided by the preparers is very well-defined, with no need for customization, so there was no need for an extensible taxonomy.</div>
<p class="tdh_072">For more information, see Improved Business Process Through XBRL: A Use Case for Business Reporting:</p>  

<p class="tdh_031"><u><a href="https://xbrl.us/wp-content/uploads/2007/12/20060202FFIECWhitePaper.pdf">https://xbrl.us/wp-content/uploads/2007/12/20060202FFIECWhitePaper.pdf</a></u></p>  

<div class="tdh_027"><a name="a_Toc24107574"></a><a name="a_Toc23337720"></a>9.2   Business to Government Reporting</div>
<div class="tdh_066">In many countries, XBRL has been implemented to standardize business financial reporting while reducing preparer burden. Australia, the Netherlands, Finland, and Ukraine have developed programs based on the XBRL standard called Standard Business Reporting (SBR) that harmonizes the definitions used in reporting, lowering the cost of sourcing information across different government agencies. Facts reported in SBR are machine-readable, consistent, clearly defined, and agreed upon by all members of the supply chain. As a result, the information is unambiguous to the preparer, regulators, and other users of the data.</div>
<p class="tdh_020"><span class="tdh_024">9.2.1     </span>How SBR Works in Australia</p>  

<div class="tdh_066">In 2010, Australia implemented an SBR program. Today nine government agencies rely on SBR to obtain financial information from regulated entities, which means that there is a uniform reporting standard across these regulatory groups. Reporting entities are required to use one of several approved software development tools that can generate XBRL-formatted data. The government provides resources to software developers who wish to become certified as &#8220;SBR-enabled&#8221;. Businesses that use SBR-enabled software can then report using information already recorded as part of running their business.</div>
<div class="tdh_066">When a report is required, SBR-enabled software knows what information is needed for that report and completes the necessary disclosures. These SBR-enabled software packages tell preparers what they need to report by leveraging the government-provided XBRL taxonomy. The software also uses agency-specific rules to validate reports for errors prior to submission to the government agencies. Once the data is submitted, it becomes available to the participating government agencies. Businesses no longer need to report information to multiple agencies through different forms or portals.</div>
<p class="tdh_026">9.2.1.1     The SBR AU Taxonomy</p>  

<div class="tdh_066">The SBR program relies upon the SBR AU Taxonomy, a collection of data elements that may be required to be reported by business to government agencies. The SBR AU Taxonomy is a recognized standard in the <a href="http://www.finance.gov.au/policy-guides-procurement/national-standards-framework">Australian National Standards Framework</a> for cross-agency interaction. The agreed-upon data elements and their associated definitions are used in the creation of machine-readable reports to be submitted by a business to agencies using SBR. The data elements are defined once and reused across multiple forms and multiple agencies.</div>
<div class="tdh_066">In developing the taxonomy, each SBR agency identified and defined the data elements required for their forms in scope. Elements in the taxonomy were then put through a process to agree on the minimal set of data elements for the SBR AU Taxonomy, which were then identified and named uniquely. Duplications were consolidated under one name.</div>
<p class="tdh_026">9.2.1.2     Governance</p>  

<div class="tdh_066">Updating existing or adding new data elements relies on an SBR change and governance process for approval by all SBR agencies. The program is managed by the Australian Business Register (ABR) Board which provides broad strategic oversight of the SBR program in conjunction with its wider role in advancing the ABR as the source of registered business information for government and businesses. Members of the ABR include senior representatives from each of the agencies involved in the program, three representatives from the states and territories, one local government representative and four business representatives, including digital service providers. The SBR Steering Group guides the development of SBR initiatives to ensure effective and responsive management for both ongoing operations and the development of new initiatives for consideration by the ABR Board. The SBR Steering</div>
<p><!-- Field: Page; Sequence: 118 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->113<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">Group also provides endorsement, assurance and guidance on proposals, monitors performance against benefits expectations, and resolves cross agency issues.</div>
<p class="tdh_020"><span class="tdh_024">9.2.2     </span>Results</p>  

<div class="tdh_066">As a result of implementing SBR, businesses spend less time collecting data, filling in forms, and submitting reports to government agencies. SBR reduces cost and fosters greater efficiency for government agencies. SBR also helps digital service providers and data intermediaries by increasing productivity and reducing manual data entry, which eliminates translation risk and increases certainty in the accuracy of the data.  The result for businesses is less time spent collating information, filling in forms, and submitting reports to participating government agencies. The only cost to business is the investment in SBR-enabled software.</div>
<div class="tdh_066">In the annual report from the Australian Taxation Authority for 2017-2018, annual (recurring) savings were estimated at $1.45 billion AUD from SBR. This translates to approximately $980 million in US dollars.</div>
<p class="tdh_020"><span class="tdh_024">9.2.3     </span>Conclusions</p>  

<div class="tdh_066">This success story illustrates how XBRL can be used to implement uniform reporting requirements and streamline regulatory compliance. Prior to the implementation of SBR, there were disparate reporting procedures for the government agencies that required the information. Through the SBR taxonomy, these requirements and procedures could be harmonized. Like the banking example in the previous section, involving software developers and vendors, allowed the implementation of agency-specific validation in addition to making it simpler for preparers to determine what information needed to be reported. Preparers can leverage a single Taxonomy to submit all the necessary information to multiple government agencies; and that information can be transported in a structured, predictable manner to one or more of the agencies involved.</div>
<p class="tdh_069">For more information on benefits, visit:<br />
<a href="https://www.sbr.gov.au/about-sbr/benefits-sbr#BenefitstoGovernment"><span class="tdh_035"><i><u>https://www.sbr.gov.au/about-sbr/benefits-sbr#BenefitstoGovernment</u></i></span></a></p>  

<div class="tdh_027"><a name="a_Toc24107575"></a><a name="a_Toc23337721"></a><a name="a_tu7jqxr0dqjs"></a><a name="a_gvjdeze91ydm"></a>9.3   Work-in-Process Reporting for Surety Underwriting</div>
<div class="tdh_066">The Work-in-Process Reporting is a standards implementation that is driven solely by industry support for improving efficiency and reducing unnecessary costs. There is no regulatory compliance driver.</div>
<div class="tdh_066">The surety underwriting process requires the evaluation of financial data collected from contractors to identify risks and determine eligibility for surety bonds. Reported data includes financial statements and Work-in-process (WIP) reports (Figure 9-2) that describe the financial performance and status of a contractor&#8217;s individual construction projects. WIP reports contain data on revenues, costs, and profit for each contract or job; they can be prepared for completed contracts or for contracts in process and may be submitted quarterly or annually.</div>
<p class="tdh_099"><img class="tdh_116" src="http://files.xbrl.us/images/tdh/tdh_p1_figure_92.jpg" alt="" /></p>  

<p class="tdh_106"><a name="a_Ref23245532"></a>Figure 9-2. An example Work-in-process report</p>  

<div class="tdh_066">WIP reports have multiple use cases, including: 1) to monitor the health of a bond written by a surety for a specific contract; 2) for surety claims processing; and 3) for delivery to the Small Business Administration</div>
<p><!-- Field: Page; Sequence: 119 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->114<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">(SBA) to monitor contractor financial health to participate in the SBA surety bond guarantee program. This section will focus on the first example, use of the WIP to monitor ongoing health of a contractor as part of the underwriting process.</div>
<p class="tdh_020"><a name="a_i64ql2wsm0vq"></a><span class="tdh_024">9.3.1     </span>Background</p>  

<div class="tdh_066">Surety is a specialized line of insurance that requires timely financial information to be shared between multiple parties. Because there is no regulatory body involved, the industry requires a method of standardizing the format and content of this information.</div>
<div class="tdh_066">Surety involves at least three parties: 1) the principal (contractor), which is the party that undertakes the obligation; 2) the surety carrier, which guarantees that the obligation (work) will be performed; and 3) the obligee, who is the owner of the project and who receives the benefit of the work and the protection of the bond.</div>
<div class="tdh_066">Typically, there is a fourth party called a bond producer (also called surety agent), which is a licensed producer serving as an intermediary between the contractor and the surety. Contractors work with bond producers who identify sureties that will be a good match for a contractor, based on size, industry and other factors. Once the relationship between the contractor and surety is in place, the bond producer continues to advise the two parties. The bond producer often receives financials and other materials from the contractor for review before they are shared with the surety.</div>
<div class="tdh_066">To request a bond, the contractor submits, through its bond producer, financials and other supporting documents. A single surety usually provides all of the bonds needed by a contractor for all of its bonded projects. <a name="a_5m964amq83es"></a></div>
<p class="tdh_020"><span class="tdh_024">9.3.2     </span>Before Data Standards</p>  

<div class="tdh_066">The contractor provided periodic financial updates to the surety including financial statements and the WIP report, which was possibly generated from the contractor&#8217;s internal financial system or through a spreadsheet application.</div>
<div class="tdh_066">When the surety received the WIP report, it was re-keyed into the surety&#8217;s financial systems, a task which was likely performed by data entry staff, entry-level underwriters, or by an assistant to the underwriter. Data was checked for accuracy. WIP data was then used to assess the health of the contractor and the contactor&#8217;s ability to successfully complete the contract.</div>
<div class="tdh_066">Time spent re-keying information depended on the length of the WIP report. For example, an account with ten jobs could take 25-40 minutes to input, one with 25 jobs was estimated to take approximately an hour, and a WIP report with hundreds of projects could take hours to complete. It was not uncommon for sureties to process thousands of WIP reports each year, equating to thousands of hours of inefficient processing time.</div>
<p class="tdh_020"><a name="a_eyivrhz41whc"></a><span class="tdh_024">9.3.3     </span>Incorporating Data Standards</p>  

<div class="tdh_066">XBRL US was approached by a small group of surety insurance companies who were interested in learning how data standards might improve efficiencies in the data collection portion of their underwriting process. They had been investigating standardization for some time and knew that they could reduce costs and establish better processes, but until learning about XBRL they had not identified how to operationalize it. A small working group, comprised of accounting professionals, sureties, bond agents, and software companies, was formed to begin developing a small taxonomy to represent the Work in Process report. While the industry group ultimately wanted all contractor financials to be in standardized, machine-readable form, the Work in Process report was seen as a good opportunity for a pilot. In this case study, the sponsor was the surety industry, rather than a regulator. The industry itself saw data standards as a tool that could improve their processes. Stakeholders included surety insurance companies, bond agents, contractors, accountants and software providers who served contractors. Eventually other stakeholders were engaged, including the Small Business Administration, which operates an SBA Surety Guarantee program where it, too, collects Work in Process reports to gauge the financial health of contractors to which it provides surety guarantees.</div>
<p><!-- Field: Page; Sequence: 120 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->115<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">The first surety to adopt the XBRL standard internally to consume XBRL-formatted WIP reports was the Hartford. To implement the taxonomy, the Hartford mapped the 70 data field labels in the taxonomy to the field labels in their internal financial system. The details available for each data field in the taxonomy made it relatively easy to perform the mapping because of the clear definitions. With the new standardized process, when a WIP report in XBRL format is received by the Hartford, the underwriter can automatically populate the database with figures from a contractor WIP using a single keystroke. Previously the implementation process for the Hartford took one individual approximately 8 hours, with approximately 50 hours for testing.</div>
<div class="tdh_066">The biggest challenge to the adoption process has been engaging contractors to prepare their WIP reports and financials in XBRL format. Several tools have been developed to aid in that process. Altova has created an Excel Add-in tool. Crowe LLP, an accounting firm that also builds software applications, has created a tool that transforms any kind of document into XBRL format. Crowe has had success working with sureties who use the application to translate documents they receive from contractors into XBRL, which they can then automatically incorporate into their financial systems. XBRL US has partnered with the National Association of Surety Bond Producers (NASBP) to create an Excel spreadsheet template that contractors or their service providers (bond agents or accountants) can use to build a WIP report and then export an XBRL version of that report. This application has been adapted for a pilot program to be used with the SBA.</div>
<div class="tdh_066">The adoption process in the surety industry is still ongoing. However, several surety carriers have adapted their internal systems to be able to consume XBRL-formatted documents, and more tools are coming on the market that can prepare XBRL documents for contractors.</div>
<p class="tdh_020"><span class="tdh_024">9.3.4     </span>Results</p>  

<div class="tdh_066">Before standards, manual entry of a WIP report containing thirteen rows of data, would have been a 30-minute exercise. With standards, the process now takes about three seconds. For the Hartford, the data is immediately live, stored in its database and ready to be used in credit models. A WIP report containing hundreds of additional rows of data would take the same three second timeframe to incorporate into the Hartford&#8217;s database. Between the anticipated technology cost for full implementation and the anticipated efficiency gains, the Hartford expects to cover implementation costs after approximately 110 WIPs are processed through the new method.</div>
<p class="tdh_020"><span class="tdh_024">9.3.5     </span>Conclusions</p>  

<div class="tdh_066">The Surety Work In Process taxonomy is a great example of an industry itself identifying a lack in data standards and working together to implement a strong XBRL solution. With the aid of XBRL US, members of the surety industry were able to address a lack of structured reporting that was hampering both comparability and efficiency through creating a better, more uniform reporting standard. The sponsor was the industry itself, and the taxonomy working groups and committees were made of industry stakeholders. There was no need for overarching regulation. This illustrates the ability of an industry to organize the goals and requirements of the XBRL taxonomy and successfully design and implement one. As more members of the surety community adopt the XBRL taxonomy for us, the gains in developing and implementing a new data standard will increase.</div>
<div class="tdh_027"><a name="a_Toc24107576"></a><a name="a_Toc23337722"></a><a name="a_qzmicvlzvawd"></a>9.4   Public Company Reporting in the United States</div>
<div class="tdh_066">The mission of the United States Securities and Exchange Commission (SEC) is to protect investors, maintain fair, orderly, and efficient markets, and facilitate capital formation. Financial disclosure requirements are a critical aspect of their mission.</div>
<div class="tdh_066">On January 30, 2009, the SEC adopted a rule entitled <i>Interactive Data to Improve Financial Reporting<a class="tdh_040" href="#note_ftn4" name="note_ftnref4">4</a></i>. The text of the rule noted: &#8220;The new rules are intended not only to make financial information easier for investors to analyze, but also to assist in automating regulatory filings and business information</div>
<hr class="tdh_260" align="left" size="1" />
<div class="tdh_066"><a class="tdh_040" href="#note_ftnref4" name="note_ftn4">4</a> <a href="https://www.sec.gov/rules/final/2009/33-9002.pdf"><span class="tdh_035"><i><u>https://www.sec.gov/rules/final/2009/33-9002.pdf</u></i></span></a></div>
<p><!-- Field: Page; Sequence: 121 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->116<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066">processing. Interactive data has the potential to increase the speed, accuracy and usability of financial disclosure, and eventually reduce costs.&#8221; The rule required public companies in the United States, foreign private issuers that prepare their financial statements in accordance with U.S. Generally Accepted Accounting Principles (U.S. GAAP), and foreign private issuers that prepare their financial statements using International Financial Reporting Standards (IFRS) to submit face financials and footnote disclosures in XBRL format. Footnote disclosures were required to be tagged using four levels of detail: 1) each complete footnote tagged as a single block of text; 2) each significant accounting policy tagged as a single block of text; 3) each table within each footnote tagged as a separate block of text; and 4) within each footnote, each amount (i.e., monetary value, percentage, and number) separately tagged.</div>
<div class="tdh_066">To accomplish the new data standards, the U.S. GAAP financial taxonomy was created at the request of the SEC. This taxonomy is now actively maintained by the Financial Accounting Standards Board (FASB). At the start of the implementation of the SEC requirements, companies were required to make two submissions: their traditional filing in HTML or text and the new requirement for the XBRL report submission. They also were required to post their XBRL report on their corporate website. The rule was phased in over a three-year period. Foreign private issuers that prepared their statements in IFRS were required to begin filing in XBRL in the third year of the phase-in, when the IFRS taxonomy, created by the International Accounting Standards Board (IASB), was accepted by the SEC in 2017.</div>
<div class="tdh_066">To further reduce preparer burden during this implementation process, companies were required to provide increasing levels of detail in their submissions over time. Initially, certain financial data was provided solely as a text block. In subsequent years, discrete data points within the text blocks were also required to be tagged. Other accommodations and support were provided to ease preparers into these new processes. This is an example of taxonomy developers and regulators instantiating a system to help preparers adopt to a novel data standard.</div>
<p class="tdh_020"><span class="tdh_024">9.4.1     </span>Before Data Standards</p>  

<div class="tdh_066">Before XBRL was implemented, corporate reporting required SEC filers to prepare financial statements in either HTML or text and submit them into the SEC&#8217;s Electronic Data Gathering and Retrieval System (EDGAR). The SEC then made the HTML/text files available to the public within minutes of their submission. Database providers, analysts, and investors could access the data through the company filings portion of the SEC&#8217;s website by searching on company name, type of filing submission, or simply looking at the latest filings. Data providers could get a feed of corporate filings and then typically parse the data to extract information into their databases, which was then resold to investors, analysts, the media, researchers, academia, other regulators, and other data consumers.</div>
<div class="tdh_066">The EDGAR system, which was put in place in 1983, was a huge step forward for disclosure. For the first time, electronic documents in text, and later in HTML format, were publicly available for anyone with internet access. Prior to the EDGAR System, corporate filings were available directly from the company or by visiting the SEC offices. In addition, EDGAR made these electronic filings readily available so that investors or other data users could download full documents electronically. Still, the data was trapped in the filing documents and required manual parsing before it could be used for analysis.</div>
<p class="tdh_020"><span class="tdh_024">9.4.2     </span>Incorporating Data Standards</p>  

<div class="tdh_066">XBRL-formatted reports were the next big revolution in disclosure. Structured data standards meant that machine-readable data, rather than just documents, are available to investors. The data can be automatically extracted. Since the introduction in 2009, there have been several important developments:</div>
<ul>
<li><span class="tdh_190">The IFRS Taxonomy was approved by the SEC, which increased the universe of companies reporting in XBRL format to include foreign entities</span></li>
<li><span class="tdh_190">Inline XBRL was mandated, which eliminated the duplicate filing of the &#8220;traditional&#8221; submission plus the XBRL. Companies today are moving towards a single Inline XBRL filing, which is a combined HTML and XBRL document.</span></li>
<li><span class="tdh_190">Many companies have migrated away from add-on tools (preparing their &#8220;paper-based&#8221; filing first before tagging it in XBRL) towards disclosure management solutions which allow for seamless integration of XBRL formatting into their disclosure process.<a name="a_hcm98yod4rzv"></a></span></li>
</ul>
<p><!-- Field: Page; Sequence: 122 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->117<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_020"><span class="tdh_024">9.4.3     </span>Results</p>  

<p class="tdh_072">The SEC program is large and complex, involving thousands of companies working with a taxonomy that today contains around 15,000 concepts based on a flexible accounting standard. The challenges in developing and implementing this standard were significant, but the industry is now seeing the following results:</p>  

<ul>
<li><span class="tdh_190">Companies are able to adapt to new taxonomy releases easily. 6,000 public companies submit machine-readable filings every quarter, and each year these companies seamlessly transition to a new version of the US GAAP Taxonomy, which has been revised to accommodate changing accounting standards as well as investor and industry requirements.</span></li>
<li><span class="tdh_190">Processing of financial data is significantly faster in an XBRL format. Morningstar, which is a financial data intermediary, cited a significant reduction in processing time with XBRL, noting that extracting data from an HTML filing took around 20 minutes, from good quality PDF around 30 minutes, and from image filing around 50 minutes, as compared to XBRL, which takes 1-2 minutes. This kind of time reduction translates into lowered costs and the ability to make data available to investors and other data users much faster. This, in turn, lowers the cost of performing analysis and increases its timeliness.</span></li>
<li><span class="tdh_190">The playing field between large and small companies has become more level. Because data from small and large companies is available and accessible simultaneously, the cost of analyzing small companies is in line with all other companies.</span></li>
<li><span class="tdh_190">Investors and data providers have embraced XBRL data. Data providers, such as Refinitiv, Bloomberg, Morningstar, and Standard &amp; Poors, have all migrated to using XBRL in some form to obtain data for investment clients. The investment community has expressed interest in obtaining more data in standardized XBRL format.</span></li>
<li><span class="tdh_190">The SEC sees value in XBRL. The Commission has drafted numerous proposals calling for additional data in XBRL format, further indicating demand for machine-readable data. Proposals include requirements for standardized financials from business development companies, closed end funds, variable life insurance, and variable annuity companies.</span></li>
<li><span class="tdh_190">The cost of XBRL data preparation is declining. A 2017 study<a class="tdh_040" href="#note_ftn5" name="note_ftnref5">5</a> conducted by the AICPA and XBRL US found that the average cost of XBRL preparation was $5,500 per year, down 45% from 2014.</span></li>
<li><span class="tdh_190">XBRL data quality is increasing. XBRL US&#8217; introduction of Data Quality Rules (starting in 2015) to help public companies identify and correct errors has significantly reduced the number of quality issues in filings.</span></li>
</ul>
<p class="tdh_020"><span class="tdh_024">9.4.4     </span>Conclusions</p>  

<div class="tdh_066">Financial reporting to the SEC is a very a large and complex process, but there are key points taxonomy developers can glean from it. First, this is a prime example of a government regulator sponsoring and adopting a structured data standard, thus facilitating its use among those who must comply with regulatory standards. Second, with that in mind, preparer burden must be considered, and to aid registrants the SEC staggered the adoption period. Additionally, switching data transport formats from XBRL in XML to Inline XBRL reduces preparer cost by eliminating redundant reports and consolidating both XBRL-tagged information and human-readable text into a single submission. Implementing data quality rules also benefits preparers by guiding them through validating their own reports prior to submission. Finally, by building upon familiar pre-existing systems and standards (US GAAP accounting standards, for example, and the already functional EDGAR system), preparer burden was reduced.</div>
<div class="tdh_066">Finally, this example demonstrates the ongoing taxonomy support and maintenance phase during the taxonomy lifecycle. The taxonomies used in reporting to the SEC are updated regularly, with changes disseminated to the community in a structured, predictable way. This facilitates updates in third-party software systems as well as allowing preparers to adjust their XBRL reports ahead of reporting deadlines.</div>
<hr class="tdh_260" align="left" size="1" />
<div class="tdh_066"><a class="tdh_040" href="#note_ftnref5" name="note_ftn5">5</a> <a href="https://www.aicpa.org/press/pressreleases/2018/xbrl-costs-have-declined-according-to-aicpa-study.html"><span class="tdh_035"><i><u>https://www.aicpa.org/press/pressreleases/2018/xbrl-costs-have-declined-according-to-aicpa-study.html</u></i></span></a></div>
<p><!-- Field: Page; Sequence: 123 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->118<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Appendix start --><br />
<!-- Field: /Page --></p>  

<div class="tdh_066"><a name="a_f5qpndo8l8fi"></a></div>
<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt; float: right; margin: 8px; border: 1px solid #e2e2e2; border-bottom: none;"><a href="#toc">Table of Contents</a></div>
<div class="tdh_028"><a name="a_Toc24107577"></a><a name="a_Toc23337723"></a><a name="a_Ref13584559"></a>Appendix   A<span class="tdh_096">         </span></div>
<p><!-- Field: Page; Sequence: 124 -- --><br />
<!--


<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo --119<!-- Field: /Sequence </span></div>


--><br />
<!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_029">XBRL and XML Supporting Information</p>  

<div class="tdh_066"><b>To be completed in a subsequent release</b></div>
<p><!-- Field: Page; Sequence: 125 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->120<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_028"><a name="a_Toc24107578"></a><a name="a_Toc23337724"></a><a name="a_Ref13653029"></a><a name="a_Ref13652551"></a><a name="a_Ref13652213"></a><a name="a_Ref13652086"></a><a name="a_Ref13645519"></a><a name="a_Ref13645515"></a><a name="a_Ref13645514"></a><a name="a_Ref13645513"></a>Appendix   B<span class="tdh_096">         </span></div>
<p><!-- Field: Page; Sequence: 126 -- --><br />
<!--


<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo --121<!-- Field: /Sequence </span></div>


--><br />
<!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_029">Taxonomy Creation Checklist</p>  

<div class="tdh_066">Note that this checklist is a tool of approximate tasks/steps for each stage of the taxonomy lifecycle. Not all steps may apply in every development situation.</div>
<p class="tdh_065"><b>BUILD</b></p>  

<div class="tdh_066"><i>General</i>:</div>
<p class="tdh_061"><span class="tdh_037">☐</span> Determine business use case</p>  

<p class="tdh_061"><span class="tdh_037">☐</span> Name taxonomy sponsor</p>  

<p class="tdh_061"><span class="tdh_037">☐</span> Determine primary stakeholders</p>  

<p class="tdh_061"><span class="tdh_037">☐</span> Determine use cases</p>  

<p class="tdh_061"><span class="tdh_037">☐</span> Determine functional and non-functional requirements</p>  

<p class="tdh_061"><span class="tdh_037">☐</span> Form taxonomy working groups/steering committees</p>  

<p class="tdh_061"><span class="tdh_037">☐</span> Determine resources required</p>  

<p class="tdh_052"><span class="tdh_037">☐</span> Create and release taxonomy white paper</p>  

<div class="tdh_066"><i>Taxonomy working group/developers:</i></div>
<p class="tdh_058"><span class="tdh_037">☐</span> Examine current systems/data sets</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Develop conceptual data model</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Determine and examine minimum data set:</p>  

<blockquote class="tdh_190"><p><span class="tdh_037">☐</span> 1. Identify dimensions<br />
<span class="tdh_037">☐</span> 2. Identify the data that is to be represented in XBRL<br />
<span class="tdh_037">☐</span> 3. Determine the minimum number of XBRL dimensions to maintain uniqueness<br />
<span class="tdh_037">☐</span> 4. Identify where arbitrary XBRL dimensions are necessary to maintain uniqueness</p>  
</blockquote>
<p class="tdh_058"><span class="tdh_037">☐</span> Develop logical data model</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Create concepts and determine concept properties</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Implement/create data types</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Determine concept core dimensions and taxonomy-defined dimensions</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Determine if taxonomy-defined dimensions should be typed or explicit</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Determine other concept relationships (calculations, definitions, etc.)</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Develop physical data model (transport model)</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Organize concepts into tables (with hypercubes as necessary)</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Organize tables and other data structures into presentations</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Organize presentations into entry points</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Physically build taxonomy files (schema and linkbase files)</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Document taxonomy throughout process</p>  

<p class="tdh_060"><i>Taxonomy steering committee:</i></p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Design adoption and implementation systems</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Ensure software development is proceeding as necessary</p>  

<p><!-- Field: Page; Sequence: 127 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->121<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_065"><b>PILOT</b></p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Conduct rigorous internal testing based on use cases and requirements</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Develop sample instance documents</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Develop, document, and implement validation and data quality standards</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Perform internal revision cycle</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Package candidate taxonomy deliverables for public exposure</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Conduct public exposure</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Evaluate comments and incorporate changes</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Build draft taxonomy</p>  

<p class="tdh_065"><b>IMPLEMENTATION</b></p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Deploy taxonomy</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Deploy documentation</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Ensure supports are available</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Design support and maintenance plans</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Determine regularity of/conditions for updates</p>  

<p class="tdh_065"><b>SUPPORT AND MAINTENANCE*</b></p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Implement required updates/changes</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Perform internal testing and revision</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Release candidate taxonomy for public exposure</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Implement suggested updates/changes as draft taxonomy</p>  

<p class="tdh_058"><span class="tdh_037">☐</span> Release draft taxonomy</p>  

<p class="tdh_098">* Repeat process for each release cycle.</p>  

<p><!-- Field: Page; Sequence: 128 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->122<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_028"><a name="a_Toc24107579"></a><a name="a_Toc23337725"></a><a name="a_Ref17884191"></a><a name="a_Ref17881971"></a>Appendix   C<span class="tdh_096">         </span></div>
<p><!-- Field: Page; Sequence: 129 -- --><br />
<!--


<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->124<!-- Field: /Sequence </span></div>


--><br />
<!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_029">Taxonomy White Paper Outline and Template</p>  

<p class="tdh_054">A version of this document is available at <a href="https://xbrl.us/tdh-templates"><span class="tdh_035"><i><u>https://xbrl.us/tdh-templates</u></i></span></a>. It provides a starting point for creating a white paper for a proposed taxonomy. See Chapter 7 for further information on the proposed structure and purpose of a Taxonomy White Paper.</p>  

<p class="tdh_053"><img class="tdh_173" src="http://files.xbrl.us/images/tdh/tdh_p1_050.jpg" alt="" /></p>  

<p><!-- Field: Page; Sequence: 130 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->123<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_099"><img class="tdh_168" src="http://files.xbrl.us/images/tdh/tdh_p1_051.jpg" alt="" /></p>  

<p><!-- Field: Page; Sequence: 131 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->124<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_028"><a name="a_Ref13652821"></a><a name="a_Ref13652722"></a><a name="a_Ref13652705"></a><a name="a_Ref13652700"></a><a name="a_Ref13652652"></a><a name="a_Toc24107580"></a><a name="a_Toc23337726"></a><a name="a_Ref14343396"></a>Appendix   D<span class="tdh_096">         </span></div>
<p><!-- Field: Page; Sequence: 132 -- --><br />
<!--


<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo --127<!-- Field: /Sequence </span></div>


--><br />
<!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_029">XBRL Overview Outline and Template</p>  

<div class="tdh_066">A version of this document is available at <a href="https://xbrl.us/tdh-templates"><span class="tdh_035"><i><u>https://xbrl.us/tdh-templates</u></i></span></a>. It provides a brief, general overview of what XBRL is and how it represents data for readers unfamiliar with it. This document can be incorporated into the <i>Taxonomy Guide</i>, <i>Preparer Guide</i>, and <i>Data Consumer Guide</i>. See Chapter 7 for more information.</div>
<div class="tdh_066"><img class="tdh_170" src="http://files.xbrl.us/images/tdh/tdh_p1_052.jpg" alt="A screenshot of a social media post Description automatically generated" /></div>
<p><!-- Field: Page; Sequence: 133 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->125<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066"><img class="tdh_174" src="http://files.xbrl.us/images/tdh/tdh_p1_053.jpg" alt="A screenshot of a cell phone Description automatically generated" /></div>
<p><!-- Field: Page; Sequence: 134 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->126<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066"><img class="tdh_174" src="http://files.xbrl.us/images/tdh/tdh_p1_054.jpg" alt="A screenshot of a cell phone Description automatically generated" /></div>
<p><!-- Field: Page; Sequence: 135 --


<div style="margin-top: 12pt; margin-bottom: 6pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">


<td style="width: 50%; font: bold 9pt Arial, Helvetica, Sans-Serif; border-bottom: rgb(153,153,153) 1pt solid; padding-bottom: 6pt-->
<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->127<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066"><img class="tdh_174" src="http://files.xbrl.us/images/tdh/tdh_p1_055.jpg" alt="A screenshot of a social media post Description automatically generated" /></div>
<p><!-- Field: Page; Sequence: 136 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->128<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066"><img class="tdh_174" src="http://files.xbrl.us/images/tdh/tdh_p1_056.jpg" alt="" /></div>
<p><!-- Field: Page; Sequence: 137 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->129<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066"><img class="tdh_166" src="http://files.xbrl.us/images/tdh/tdh_p1_057.jpg" alt="A screenshot of a social media post Description automatically generated" /></div>
<p class="tdh_065">(remainder of page intentionally left blank)</p>  

<p><!-- Field: Page; Sequence: 138 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->130<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_028"><a name="a_Toc24107581"></a><a name="a_Toc23337727"></a><a name="a_Ref14859972"></a>Appendix   E<span class="tdh_096">         </span></div>
<p><!-- Field: Page; Sequence: 139 -- --><br />
<!--


<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo --134<!-- Field: /Sequence </span></div>


--><br />
<!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_029">Taxonomy Guide Outline and Template</p>  

<div class="tdh_066">A version of this document is available at <a href="https://xbrl.us/tdh-templates"><span class="tdh_035"><i><u>https://xbrl.us/tdh-templates</u></i></span></a>. It provides a starting point for creating a <i>Taxonomy Guide</i> for the developed and implemented taxonomy. See Chapter 7 for further information on the proposed content and structure of a <i>Taxonomy Guide</i>.</div>
<p class="tdh_065"><img class="tdh_169" src="http://files.xbrl.us/images/tdh/tdh_p1_058.jpg" alt="A screenshot of a social media post Description automatically generated" /></p>  

<p><!-- Field: Page; Sequence: 140 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->131<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_065"><img class="tdh_174" src="http://files.xbrl.us/images/tdh/tdh_p1_059.jpg" alt="A screenshot of a social media post Description automatically generated" /></p>  

<p><!-- Field: Page; Sequence: 141 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->132<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_079"><img class="tdh_174" src="http://files.xbrl.us/images/tdh/tdh_p1_060.jpg" alt="A screenshot of a social media post Description automatically generated" /></p>  

<p><!-- Field: Page; Sequence: 142 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->133<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_099"><img class="tdh_174" src="http://files.xbrl.us/images/tdh/tdh_p1_061.jpg" alt="A screenshot of a social media post Description automatically generated" /></p>  

<p><!-- Field: Page; Sequence: 143 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->134<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_065"><img class="tdh_154" src="http://files.xbrl.us/images/tdh/tdh_p1_062.jpg" alt="A screenshot of a social media post Description automatically generated" /></p>  

<p class="tdh_065">(remainder of page intentionally left blank)</p>  

<p><!-- Field: Page; Sequence: 144 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->135<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_028"><a name="a_Toc24107582"></a><a name="a_Toc23337728"></a><a name="a_Ref18930542"></a><a name="a_Ref13652737"></a>Appendix   F<span class="tdh_096">          </span></div>
<p><!-- Field: Page; Sequence: 145 -- --><br />
<!--


<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo --140<!-- Field: /Sequence </span></div>


--><br />
<!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_029">Preparer Guide Outline and Template</p>  

<div class="tdh_066">A version of this document is available at <a href="https://xbrl.us/tdh-templates"><span class="tdh_035"><i><u>https://xbrl.us/tdh-templates</u></i></span></a>. It provides a starting point for creating a <i>Preparer Guide</i> for the developed and implemented taxonomy. See Chapter 7 for further information on the proposed content and structure of a <i>Preparer Guide</i>.</div>
<p class="tdh_065"><img class="tdh_171" src="http://files.xbrl.us/images/tdh/tdh_p1_063.jpg" alt="" /></p>  

<p><!-- Field: Page; Sequence: 146 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->136<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_079"><img class="tdh_174" src="http://files.xbrl.us/images/tdh/tdh_p1_064.jpg" alt="A screenshot of a cell phone Description automatically generated" /></p>  

<p><!-- Field: Page; Sequence: 147 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->137<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_079"><img class="tdh_174" src="http://files.xbrl.us/images/tdh/tdh_p1_065.jpg" alt="A screenshot of a social media post Description automatically generated" /></p>  

<p><!-- Field: Page; Sequence: 148 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->138<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_065"><img class="tdh_174" src="http://files.xbrl.us/images/tdh/tdh_p1_066.jpg" alt="A screenshot of a social media post Description automatically generated" /></p>  

<p><!-- Field: Page; Sequence: 149 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->139<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_065"><img class="tdh_165" src="http://files.xbrl.us/images/tdh/tdh_p1_067.jpg" alt="A screenshot of a social media post Description automatically generated" /></p>  

<p class="tdh_065">(remainder of page intentionally left blank)</p>  

<p><!-- Field: Page; Sequence: 150 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->140<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_028"><a name="a_Toc24107583"></a><a name="a_Toc23337729"></a><a name="a_Ref17882889"></a><a name="a_Ref17882699"></a><a name="a_Ref13652766"></a>Appendix   G<span class="tdh_096">        </span></div>
<p><!-- Field: Page; Sequence: 151 -- --><br />
<!--


<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo --146<!-- Field: /Sequence </span></div>


--><br />
<!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_029">Data Consumer Guide Outline and Template</p>  

<div class="tdh_066">A version of this document is available at <a href="https://xbrl.us/tdh-templates"><span class="tdh_035"><i><u>https://xbrl.us/tdh-templates</u></i></span></a>. It provides a starting point for creating a <i>Data Consumer Guide</i> for the developed and implemented taxonomy. See Chapter 7 for further information on the proposed content and structure of a <i>Data Consumer Guide</i>.</div>
<p class="tdh_071"><img class="tdh_172" src="http://files.xbrl.us/images/tdh/tdh_p1_068.jpg" alt="" /></p>  

<p><!-- Field: Page; Sequence: 152 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->141<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_079"><img class="tdh_174" src="http://files.xbrl.us/images/tdh/tdh_p1_069.jpg" alt="A screenshot of a cell phone Description automatically generated" /></p>  

<p><!-- Field: Page; Sequence: 153 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->142<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_079"><img class="tdh_174" src="http://files.xbrl.us/images/tdh/tdh_p1_070.jpg" alt="A screenshot of a social media post Description automatically generated" /></p>  

<p><!-- Field: Page; Sequence: 154 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->143<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_065"><img class="tdh_148" src="http://files.xbrl.us/images/tdh/tdh_p1_071.jpg" alt="A screenshot of a social media post Description automatically generated" /></p>  

<p class="tdh_065">(remainder of page intentionally left blank)</p>  

<p><!-- Field: Page; Sequence: 155 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->144<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_028"><a name="a_Toc24107584"></a><a name="a_Toc23337730"></a>Appendix   H<span class="tdh_096">         </span></div>
<p><!-- Field: Page; Sequence: 156 -- --><br />
<!--


<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo --151<!-- Field: /Sequence </span></div>


--><br />
<!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_029">XBRL US — Taxonomy Approval Metrics</p>  

<div class="tdh_066">The latest version of the Taxonomy Approval Metrics (TAM) is available at <a href="/xbrl-reference/tam">xbrl.ux/tam</a>. The following is a synopsis of the process and metrics from the May 2018 TAM, the process of approval is described at the previously described URL.</div>
<div class="tdh_066">While it is not required to have a taxonomy approved, it is a good step in developing a comprehensive taxonomy. Using this list will also aid in review the product during development.</div>
<p class="tdh_090"><b>Taxonomy Metrics (from TAM)</b></p>  

<div id="tam-tdh">
<ol>
<li><span class="tdh_190"><span class="primary">The Taxonomy Describes the Disclosed Data Architecture / Semantics</span></span>
<ol>
<li><span class="tdh_190"><a name="7"></a><span class="secondary">Requirements Addressed</span></span>
<ol>
<li><span class="tdh_190">Business requirements MUST be adequately and clearly described.</span></li>
<li><span class="tdh_190">Existing system(s), if any, SHOULD be described adequately and the differences between the proposed Taxonomy and existing system(s) enumerated.</span></li>
<li><span class="tdh_190">All stakeholders MUST be properly identified and aligned.</span></li>
<li><span class="tdh_190">Key stakeholder groups MUST be identified as participants in development.</span></li>
<li><span class="tdh_190">Developer SHOULD enumerate methods in which the Taxonomy exchanges information more efficiently than existing or alternative approaches.</span></li>
<li><span class="tdh_190">Developer SHOULD summarize &#8216;Actors and Processes&#8217; of the above requirements.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="8"></a><span class="secondary">Shared Data Elements</span></span>
<ol>
<li><span class="tdh_190">The Taxonomy MUST define a domain or business Semantic Data Model for the exchange of information including inputs, outputs and data views.</span></li>
<li><span class="tdh_190">Importable taxonomies and shared data elements MUST be identified.</span></li>
<li><span class="tdh_190">The characteristics of each data element MUST be defined.</span></li>
<li><span class="tdh_190">Private/Confidential aspects of the data model MUST be addressed.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="9"></a><span class="secondary">Interfacing</span></span>
<ol>
<li><span class="tdh_190">Developer SHOULD define the typical source data elements and locations and addresses options for data extraction.</span></li>
<li><span class="tdh_190">Developer SHOULD define one or more rudimentary methods of viewing or presenting information in a meaningful way for preparers and consumers.</span></li>
<li><span class="tdh_190">Developer SHOULD address the level of burden to preparers and consumers on an initial and ongoing basis.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="10"></a><span class="secondary">Open or Closed Architecture</span></span>
<ol>
<li><span class="tdh_190">The Taxonomy MUST be described as either “open” or “closed”.</span></li>
<li><span class="tdh_190">If open, Developer MUST describe the extent and manner preparers can extend the taxonomy, including details of the types of extensions (concepts, dimensions, units, etc.).</span></li>
<li><span class="tdh_190">If open, Developer SHOULD define what steps, if any, are required to normalize data.</span></li>
<li><span class="tdh_190">If closed, Developer SHOULD describe the methods allowed by the Taxonomy to footnote or provide additional information.</span></li>
<li><span class="tdh_190">Developer MUST define whether XBRL footnotes may be employed and in what manner.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="11"></a><span class="secondary">Instance Only</span></span>
<ol>
<li><span class="tdh_190">Developer defines whether data within the Taxonomy can be consumed using only an instance document.</span></li>
</ol>
</li>
</ol>
</li>
<li><span class="tdh_190"><a name="12"></a><span class="primary">Support Requirements</span></span>
<ol>
<li><span class="tdh_190"><a name="13"></a><span class="secondary">Published Documentation</span></span>
<ol>
<li><span class="tdh_190">The Taxonomy MUST include an Overview Document describing the overall application, justification and approach to the development of the Taxonomy, definitions of concepts within the Taxonomy and required and optional Taxonomy data. The document SHOULD also outline revision mechanics and governing bodies.</span></li>
<li><span class="tdh_190">The Taxonomy MUST include a Preparer&#8217;s Guide to aid in the proper assembly and structure of XBRL instance data and associated linkbases.</span></li>
<li><span class="tdh_190">The Taxonomy MUST include an Implementation Guide to aid system developers in the exportation and importation of instance data components and linkbases.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="14"></a><span class="secondary">Implementation Procedures</span></span>
<ol>
<li><span class="tdh_190">Developer MUST provide internal documentation for the management of the implementation of the Taxonomy.</span></li>
<li><span class="tdh_190">Developer MUST discuss the method of implementation, impediments to implementation and major implementation milestones.</span></li>
<li><span class="tdh_190">Developer MUST include a plan for the operation of governing bodies.</span></li>
<li><span class="tdh_190">Developer MUST define related third parties that may be required or relied upon for implementation.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="15"></a><span class="secondary">Revision Procedures</span></span>
<ol>
<li><span class="tdh_190">Developer MUST provide internal documentation for the methods and procedures pertaining to revising the Taxonomy and its supporting documentation.</span></li>
<li><span class="tdh_190">Developer SHOULD create public revision procedures that SHOULD include review and comment periods.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="16"></a><span class="secondary">Tools</span></span>
<ol>
<li><span class="tdh_190">Developer MUST discuss tools for preparers, such as for validation and accuracy.</span></li>
<li><span class="tdh_190">Developer MUST discuss whether tools will be provided for consumers.</span></li>
<li><span class="tdh_190">Developer MUST provide at least two sample instance documents.</span></li>
</ol>
<p>&nbsp;</li>
</ol>
</li>
<li><span class="tdh_190"><a name="17"></a><span class="primary">General XBRL Requirements</span></span>
<ol>
<li><span class="tdh_190"><a name="18"></a><span class="secondary">XBRL Specifications</span></span>
<ol>
<li><span class="tdh_190">The Taxonomy MUST conform to existing XBRL Specifications published by <a href="https://specifications.xbrl.org/specifications.html" target="_blank" rel="noopener">XBRL International</a> and <a href="https://xbrl.us/reference-guide" target="_blank" rel="noopener">XBRL US</a>.</span></li>
<li><span class="tdh_190">Developer MUST specify any other standards or groups relied upon to create and maintain the Taxonomy.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="19"></a><span class="secondary">Data Architecture</span></span>
<ol>
<li><span class="tdh_190">Developer MUST describe the overall data architecture, including graphics, as required, to illustrate hierarchical and domain relationships.</span></li>
<li><span class="tdh_190">Developer MUST describe any required parent-child relationships.</span></li>
<li><span class="tdh_190">For repetitive submissions, Developer MUST describe whether various data elements will be reiterated for previous filings and, if so, why. If reiteration is allowed, Developer MUST describe a policy for differences from submission to submission.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="20"></a><span class="secondary">Data Types and Units</span></span>
<ol>
<li><span class="tdh_190">The Taxonomy SHOULD employ the most restrictive data types for common values. For example, if a concept can only have non-negative values (regardless of dimensionality), a non-negative data type SHOULD be employed.</span></li>
<li><span class="tdh_190">If custom data types or unit types are required for the Taxonomy, the unit type(s) to be used SHOULD be specified and a request SHOULD be made to add the custom type(s) to the appropriate XBRL registry.</span></li>
<li><span class="tdh_190">The Taxonomy MUST express which units are allowed or declare an appropriate Unit Type Registry (UTR), such as <a href="https://specifications.xbrl.org/work-product-index-registries-units-registry-1.0.html" target="_blank" rel="noopener">XBRL International&#8217;s UTR</a>, and whether extension units can be used by preparers. Any identified extension units SHOULD be added to XBRL International&#8217;s UTR.</span></li>
<li><span class="tdh_190">The Taxonomy MUST express how scaled units SHOULD be used, if at all.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="21"></a><span class="secondary">Concepts/Elements</span></span>
<ol>
<li><span class="tdh_190">The naming of elements MUST conform to XBRL requirements.</span></li>
<li><span class="tdh_190">The naming of elements MUST be consistent and clear to avoid overlapping names, excessively terse or verbose names, or ambiguous names and comply with <a href="https://xbrl.us/xbrl-reference/style-guide/" target="_blank" rel="noopener">XBRL US Style Guide</a>.</span></li>
<li><span class="tdh_190">Elements MUST be specified for context and dimensional requirements restrictions.</span></li>
<li><span class="tdh_190">The Taxonomy MUST define: (i) required and optional concepts; (ii) mutually dependent concepts; and, (iii) mutually exclusive concepts.</span></li>
<li><span class="tdh_190">If Taxonomy extensions are allowed, Developer MUST specify guidelines, rules and the scope for creating extensions.</span></li>
<li><span class="tdh_190">Each concept&#8217;s properties MUST be defined to include: (i) the period/context type (relationship in time); and, (ii) any extra information such as balance types, if applicable. These SHOULD be in conformance with the Balance Type and Period Type Guide.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="22"></a><span class="secondary">Data (Facts)</span></span>
<ol>
<li><span class="tdh_190">Each concept MUST use a defined data type included in the Taxonomy.</span></li>
<li><span class="tdh_190">Each numeric concept/fact SHOULD use a standard Unit Type from the XBRL International UTR. If a non-standard unit is necessary, the Taxonomy SHOULD clearly express the reasoning for the use of such a unit.</span></li>
<li><span class="tdh_190">Each concept SHOULD exist within the presentation or mathematical relationships of the Taxonomy.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="23"></a><span class="secondary">Labels and Label Roles</span></span>
<ol>
<li><span class="tdh_190">The Taxonomy SHOULD only use XBRL International approved label roles.</span></li>
<li><span class="tdh_190">The Taxonomy MUST provide for each concept an associated label for each applicable label role.</span></li>
<li><span class="tdh_190">The Taxonomy MUST express whether extension concepts require documentation and what that documentation SHOULD express.</span></li>
<li><span class="tdh_190">The Taxonomy MUST express whether each label role must be unique within an instance and the reasoning behind that choice.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="24"></a><span class="secondary">Presentations</span></span>
<ol>
<li><span class="tdh_190">The Taxonomy MUST define proper abstract usage and comply with the XBRL US Style Guide.</span></li>
<li><span class="tdh_190">All elements included in the Taxonomy SHOULD be represented in a presentation linkbase.</span></li>
<li><span class="tdh_190">Abstract items SHOULD be used to group elements together in logical groupings or headings.</span></li>
<li><span class="tdh_190">Developer MUST define the purpose and scope of default presentations and ad hoc presentations.</span></li>
<li><span class="tdh_190">Developer MUST define whether the concepts specified for use on a default presentation can also be used on other presentations for which the concept is not specified for use.</span></li>
<li><span class="tdh_190">The Taxonomy MUST define mandatory and optional presentations.</span></li>
<li><span class="tdh_190">The Taxonomy MUST define proper abstract usage.</span></li>
<li><span class="tdh_190">If extensions are allowed, the Taxonomy MUST require presentations to define relationships with other elements.</span></li>
<li><span class="tdh_190">The content generated from XBRL SHOULD match the existing system in structure and/or human readability.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="25"></a><span class="secondary">Mathematical Relationships</span></span>
<ol>
<li><span class="tdh_190">The Taxonomy MUST express relationships between concepts as calculations or formulae as applicable.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="26"></a><span class="secondary">Normalization</span></span>
<ol>
<li><span class="tdh_190">Developer MUST define whether normalization of data is required for consumption and, if so, to the extent practicable, the method of normalization.</span></li>
<li><span class="tdh_190">If normalization is required, Developer MUST address any potential issues.</span></li>
</ol>
</li>
</ol>
</li>
<li><span class="tdh_190"><a name="27"></a><span class="primary">XBRL Conformance Requirements</span></span>
<ol>
<li><span class="tdh_190"><a name="28"></a><span class="secondary">Taxonomy Architecture</span></span>
<ol>
<li><span class="tdh_190">The Taxonomy SHOULD comply with <a href="https://specifications.xbrl.org/work-product-index-guidance-financial-reporting-guidance.html" target="_blank" rel="noopener">FRTA 1.0 guidance</a> as published by XBRL International.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="29"></a><span class="secondary">Valid Instances</span></span>
<ol>
<li><span class="tdh_190">Valid instance documents SHOULD be provided with the Taxonomy that demonstrate the use of all fields in the Taxonomy.</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="30"></a><span class="secondary">XBRL US Conformance Tests</span></span>
<ol>
<li><span class="tdh_190">The Taxonomy MUST comply with the XBRL US conformance tests [add links final].</span></li>
</ol>
</li>
<li><span class="tdh_190"><a name="31"></a><span class="secondary">XBRL US Style Guide</span></span>
<ol>
<li><span class="tdh_190">The Taxonomy MUST comply with the XBRL US Style Guide.</span></li>
</ol>
</li>
</ol>
</li>
</ol>
</div>
<p class="tdh_065">(remainder of page intentionally left blank)</p>  

<p><!-- Field: Page; Sequence: 160 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->148<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_028"><a name="a_Toc24107585"></a><a name="a_Toc23337731"></a><a name="a_Ref13652582"></a>Appendix   I<span class="tdh_096">            </span></div>
<p><!-- Field: Page; Sequence: 161 -- --><br />
<!--


<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo --156<!-- Field: /Sequence </span></div>


--><br />
<!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_029">Intellectual Property Status</p>  

<div class="tdh_027"><a name="a_Toc24107586"></a><a name="a_Toc23337732"></a><a name="a_Toc13483113"></a>I.1.   Terms and Conditions: XBRL US Public Review</div>
<div class="tdh_066">In order to provide comments that will be considered by the Domain Steering Committee (DSC) as part of the Public Review process, you must read this page, complete the form below and click the &#8220;Accept&#8221; button.</div>
<p class="tdh_020"><span class="tdh_024">I.1.1.     </span>No Restrictions on Dissemination or Use of Information or Technology Submitted in XBRL US DSC Public Review</p>  

<div class="tdh_066">In order to meet the XBRL US mission to improve the usability of XBRL data, it is vital that the documents exposed for comment, as well as subsequent modifications, and any future versions derived from it can be used in derivative works that comment on, explain, or assist in the use or implementation of the XBRL Taxonomies in the United States. In addition, some or all of the DSC&#8217;s documentation may be used to improve materials and resources produced through the use of other taxonomies for industry stakeholders, agencies of the U.S. Government and others.</div>
<div class="tdh_066">Accordingly, as a Commenter you must not include in your comments any information or technology that cannot be freely disclosed to and used by the public. By submitting comments, you (i) acknowledge that XBRL US may publish or otherwise make available any and all such information or technology to the public or to any person for any use or purpose, and (ii) hereby assign to XBRL US all right, title and interest in any such information or technology, including any copyrights or patents therein. In addition, by providing information or technology to XBRL US as part of your comments, you represent, warrant and covenant to XBRL US that such information or technology does not and will not infringe the intellectual property rights of any third party.</div>
<div class="tdh_066">XBRL US and the volunteers working as part of the DSC Public Review process shall incur no liability to any third party, including you or other Commenters, arising from your submission of information or technology while providing comments or from any publication or use of such information or technology. By submitting information or technology, you waive any claim against XBRL US and volunteers working as part of the DSC Public Review process arising from the submission, or the publication or use, of the information or technology.</div>
<div class="tdh_066">Neither XBRL US nor any other person shall be required to pay you any royalties or other compensation arising from your submission of information or technology in your comments, or from XBRL US&#8217;s dissemination thereof, or from any use of the information or technology by a person to whom XBRL US has disclosed it.</div>
<div class="tdh_066">By receiving information or technology submitted in your comments, XBRL US shall not be deemed to accept or endorse the information or technology as meeting any standard of performance or quality or being fit for any particular use or purpose. XBRL US&#8217;s receipt or publication of such information or technology shall not give rise to any obligation on the part of XBRL US and, in particular, shall not be taken as an indication that XBRL US has conducted any evaluation or assessment of the information or technology.</div>
<div class="tdh_066">If you nonetheless wish to submit to XBRL US information or technology that is subject to restrictions on its disclosure or use, you may contact XBRL US directly to discuss the possibility of entering into a written agreement that acknowledges and gives effect to such restrictions. Absent a written agreement signed by an authorized XBRL US senior executive, however, XBRL US shall not be deemed to have agreed to any restrictions on disclosure or use of information or technology you may submit while participating in the Center for DSC Public Review process.</div>
<p><!-- Field: Page; Sequence: 162 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->149<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_020"><span class="tdh_024">I.1.2.     </span>License</p>  

<div class="tdh_066">All material produced by the DSC is copyrighted as follows, whether the copyright is carried explicitly in the material, or not in the file (such as .csv files, which have no means of embedding copyright and legal wording):</div>
<p class="tdh_065"><span class="tdh_001">© Copyright 2007–2019, XBRL US Inc. — All rights reserved</span></p>  

<div class="tdh_066">The draft documentation is being provided solely in connection with the DSC&#8217;s consideration regarding whether to eventually provide an approved/published version of the document.</div>
<p class="tdh_020"><span class="tdh_024">I.1.3.     </span>IP Statement Made During Meetings and Calls of the Working Group</p>  

<p class="tdh_080">Please be aware that this meeting is being held under the XBRL International IP Policy, which is available at the &#8220;Governing Documents&#8221; section of the <a href="https://www.xbrl.org/"><span class="tdh_035"><i><u>XBRL.org</u></i></span></a> website. Is anyone here aware of any claims under any patent applications or issued patents that would be likely to be infringed by an implementation of any work product that is the subject of this meeting? You need not be the inventor of such patent or patent application in order to inform us of its existence. No-one will be held responsible for expressing a belief that turns out to be inaccurate.</p>  

<p><!-- Field: Page; Sequence: 163 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->150<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_028"><a name="a_Toc24107587"></a><a name="a_Toc23337733"></a>Appendix   J<span class="tdh_096">          </span></div>
<p><!-- Field: Page; Sequence: 164 -- --><br />
<!--


<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo --159<!-- Field: /Sequence </span></div>


--><br />
<!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_029">Document Revision Status</p>  

<table class="tdh_077" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_204">
<td class="tdh_253"><span class="tdh_039"><b>Date</b></span></td>
<td class="tdh_257"><span class="tdh_039"><b>Editor/Contributor</b></span></td>
<td class="tdh_252"><span class="tdh_039"><b>Activity</b></span></td>
</tr>
<tr class="tdh_204">
<td class="tdh_009" colspan="3"><span class="tdh_039"><b>Revised Base Style Guide</b></span></td>
</tr>
<tr class="tdh_204">
<td class="tdh_010"><span class="tdh_039">October 2017-2019</span></td>
<td class="tdh_012">
<p class="tdh_086"><i>Chair:<br />
</i> Scott Theis (Novaworks)</p>  

<p class="tdh_087"><i>Authors:</i></p>  

<p class="tdh_087">Scott Theis (Novaworks)</p>  

<p class="tdh_087">Margaret Gardner (Novaworks)</p>  

<p class="tdh_087">David Theis (Novaworks)</p>  

<p class="tdh_087">Michelle Savage (XBRL US)</p>  

<p class="tdh_086">Campbell Pryde (XBRL US)<br />
Erin Rybinski (Novaworks)</p>  

<p class="tdh_086"><i>Editors:<br />
</i> Margaret Gardner (Novaworks)<br />
Erin Rybinski (Novaworks)<br />
Michelle Savage (XBRL US)<br />
David Theis (Novaworks)</p>  

<p class="tdh_086"><i>Contributors:<br />
</i> Joel Stiebel, CPA<br />
(Stiebel Associates)<br />
Rob Nehmer (Oakland Univ)</p>  

</td>
<td class="tdh_011"><span class="tdh_039">Initial draft of the Taxonomy Development Handbook.</span></td>
</tr>
</tbody>
</table>
<p><!-- Field: Page; Sequence: 165 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->151<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_028"><a name="a_Toc24107588"></a><a name="a_Toc23337734"></a>Appendix   K<span class="tdh_096">         </span></div>
<p><!-- Field: Page; Sequence: 166 -- --><br />
<!--


<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo --161<!-- Field: /Sequence </span></div>


--><br />
<!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_029">Revisions and Public Comments</p>  

<div class="tdh_066">The Taxonomy Development Handbook was released for public comments on November 18, 2019. Comments and responses will be placed here.</div>
<p><!-- Field: Page; Sequence: 167 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->152<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_030"><a name="a_Toc24107589"></a><a name="a_Toc23337735"></a>Glossary</p>  

<p class="tdh_051">This glossary contains terms used within this document as well as used for XBRL generally. Note that some previous terms have been deprecated in favor of more precise definitions.</p>  

<p class="tdh_070"><b>abstract property</b> — A property of a concept within a taxonomy used to indicate that the concept is only used as a node in a hierarchy to group related concepts together. An abstract concept cannot be used to define a fact in an instance document.</p>  

<p class="tdh_070"><b>arc</b> — A relationship between two or more concepts.</p>  

<p class="tdh_070"><b>arcrole</b> — A description of the relationship between two or more concepts.</p>  

<p class="tdh_070"><b>Arelle</b> — A freely available, open source software platform for viewing XBRL instance documents and designing XBRL taxonomies.</p>  

<p class="tdh_070"><b>ASCII </b>— A method of character encoding that represents 128 characters with seven-bit integers (<span class="tdh_036">American Standard Code for Information Interchange)</span>. See <i>encoding</i>.</p>  

<p class="tdh_070"><b>attribute</b> — A value for a property specific to an XML element (for example, specifying the decimal precision of a fact). The attributes that may be used are specified by the XML schema.</p>  

<p class="tdh_070"><b>authoritative reference</b> — Citations to specific authoritative accounting literature (pronouncements, standards, rules, and regulations) derived from various authoritative sources for the business, industry or regulatory agency used to help define a concept.</p>  

<p class="tdh_070"><b>axis</b> <i>or</i> <b>axes</b> — Intersecting lines that identify a fact as being in a plane or dimension (for example, <i>x</i>, <i>y</i> and <i>z</i>, or line items and periods). An axis is synonymous with a dimension.</p>  

<p class="tdh_070"><b>balance</b> <i>or</i> <b>balance type</b> — A property of a monetary concept designated as debit, credit, or neither. A designation, if any, should be the natural or most expected balance of the element &#8220;credit&#8221; or &#8220;debit&#8221; and thus indicates how calculation relationships involving the concept may be assigned a weight attribute (-1 or +1).</p>  

<p class="tdh_070"><b>build phase</b> — The stage of the taxonomy lifecycle during which taxonomy design and documentation occurs.</p>  

<p class="tdh_070"><b>business data model</b> — A semantic data model used to organize business data. Such data can contain customer/client information, products, inventory, research, accounting, and modeling information.</p>  

<p class="tdh_070"><b>calculation </b>— An additive relationship between numeric items expressed as parent/child hierarchies. Each calculation child has a weight attribute (+1 or -1) based upon its natural balance of the parent and child items. Calculations must occur between concepts along the same XBRL dimension.</p>  

<p class="tdh_070"><b>calculation linkbase</b> — An optional XML file containing the calculation relationships between concepts provided with an instance.</p>  

<p class="tdh_070"><b>camel case</b> — A method of naming a concept (XML legal name or programmatic name) that does not contain spaces or punctuation. In addition, words typically have their first letter capitalized. In upper camel case, the first word also follows this style. For example, &#8220;Net Change in Assets&#8221; becomes the concept name &#8220;NetChangeInAssets&#8221;. The <a href="https://xbrl.us/xbrl-reference/style-guide/"><span class="tdh_035"><i><u>XBRL US Style Guide</u></i></span></a> specifies naming rules.</p>  

<p class="tdh_070"><b>child</b> — A hierarchical node (concept) that has a parent node. Note that in XBRL parent/child relationships have no implied or explicit inheritance.</p>  

<p class="tdh_070"><b>closed property</b> — A property of a hypercube that specifies that all taxonomy-defined dimensions in the hypercube must intersect on a fact in order for that fact to be part of the hypercube.</p>  

<p><!-- Field: Page; Sequence: 168 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->153<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_070"><b>closed taxonomy</b> <i>or </i><b>closed reporting</b> — A taxonomy that has a narrowly defined structure and cannot be extended by the preparer.</p>  

<p class="tdh_070"><b>comma separated values (CSV)</b> — A method of representing a two-dimensional data set without any intrinsic meaning. CSV separates data fields with commas and rows as lines of data. A certain level of protected character control is provided by using quotes around the data fields. CSV can be combined with a specified structure for representing instance data for XBRL. CSV is a <i>de facto</i> standard without a formal specification or governing body.</p>  

<p class="tdh_070"><b>comparability</b> — The ability of two or more XBRL reports to be compared. The goal of a structured XBRL taxonomy is to ensure comparability of data. Some features of XBRL, such as extensibility, can reduce comparability.</p>  

<p class="tdh_070"><b>concept</b> — A defined item within a taxonomy describing semantic context for a fact. Concepts may represent a line item, an axis, a dimensional member, or an abstract used to group other concepts. For XML, element is the same as concept.</p>  

<p class="tdh_070"><b>concept core dimension</b> — The primary concept that defines the semantic meaning of a fact. The concept core dimension is required for each XBRL fact.</p>  

<p class="tdh_070"><b>concept definition</b> — The definition within a schema of the properties of the concept. A human-readable description of a reporting concept can also be provided with one or more labels. From a technical point of view, the concept definition is the label with the type &#8220;documentation&#8221;. The deprecated version of this term is element definition.</p>  

<p class="tdh_070"><b>concept group</b> — A higher level of a parent/child hierarchy used to categorize concept relationships in a table, presentation, or entry point. Abstract concepts are used as container concepts to accomplish this organization.</p>  

<p class="tdh_070"><b>concept name</b> — A concept name is the XML legal name used to identify a concept within a taxonomy. A concept name may be considered a qualified name (qname) in that it will have a namespace prefix and then a name. Concept names should follow the <a href="https://xbrl.us/xbrl-reference/style-guide/"><span class="tdh_035"><i><u>XBRL US Style Guide</u></i></span></a> rules.</p>  

<p class="tdh_070"><b>conceptual data model</b> — An early modeling step that focuses on static, overarching requirements and use cases. Conceptual data models also explore how the minimum data set fulfills these requirements.</p>  

<p class="tdh_070"><b>consumer</b> — The party or parties that receive and process XBRL instance (and linkbase) data. Consumers can include, but are not limited to, regulatory agencies, data analysts, internal departments, industry groups or the public.</p>  

<p class="tdh_070"><b>consumer data model</b> — A data model that a consumer might use to apply one or more use cases to consume instance documents from preparers to perform analysis.</p>  

<p class="tdh_070"><b>context </b>— A term used in XML instance documents to group certain XBRL dimensions, such as the period, legal entity, and other dimensional information. Contexts are defined within the XML-based and Inline XBRL instance documents that can be later refenced to place facts within those contexts.</p>  

<p class="tdh_070"><b>core dimension</b> — An XBRL dimension whose semantic meaning is defined by the <a href="https://specifications.xbrl.org/work-product-index-group-base-spec-base-spec.html"><span class="tdh_035"><i><u>XBRL Specification</u></i></span></a>. With the exception of the concept core dimension, core dimensions are specified in the XBRL instance document rather than the taxonomy schema. Certain core dimensions can default, be optional, or may not be allowed depending on the fact&#8217;s data type and other considerations. For example, the language core dimension is applicable to a text fact while the unit core dimension is applicable to numeric facts.</p>  

<p class="tdh_070"><b>cube</b> — A multi-dimensional structure having more than one data plane (also known as a <i>hypercube</i> when more than three planes are involved).</p>  

<p class="tdh_070"><b><i>Data Consumer Guide</i></b> — A document explaining common use cases relevant to the taxonomy. The <i>Data Consumer Guide</i> should contain a discussion of the taxonomy itself in so far as it is needed to understand how the taxonomy structures data relevant to the use cases. This document may be intended</p>  

<p><!-- Field: Page; Sequence: 169 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->154<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_070">for data analysts, regulators, data intermediaries, or other individuals interested in using the taxonomy to derive data about a particular industry.</p>  

<p class="tdh_070"><b>data dimensionality</b> — The inherent structure of a data set, such as a list, table, tree, or other extended data. Well defined data should have obvious dimensionality. Within XBRL, data dimensionality for a fact is defined by, at a minimum, the period core dimension, the concept core dimension, and entity core dimension. Additional dimensionality may be added by language or unit core dimensions and one or more taxonomy defined dimensions.</p>  

<p class="tdh_070"><b>data model</b> — An abstract model that organizes data points and defines how the data points within the model relate to each other and to other real-world entities.</p>  

<p class="tdh_070"><b>data point</b> — A discrete value, data item, or slot that exists within a data model. When placed into an XBRL instance, a data point becomes a fact.</p>  

<p class="tdh_070"><b>data quality</b> — The semantic integrity and factual accuracy of data.</p>  

<p class="tdh_070"><b>data quality committee</b> — A group of individuals (typically data architects, industry specialists, and other experts on data structuring and integrity) who convene to create data quality rules. These rules help ensure XBRL reports meet taxonomy-specific data quality standards.</p>  

<p class="tdh_070"><b>data type</b> — A property of a concept that constrains a fact&#8217;s content while also defining concept usage. Data types are defined in XML with derived types indicated by XBRL in the Data Type Registry. A taxonomy may employ several DTR references and contain custom data types.</p>  

<p class="tdh_070"><b>data type registry (DTR)</b> — A registry of well-known well-defined data types based on standard XML types and expanded by XBRL specifications and taxonomies. See the <a href="https://specifications.xbrl.org/work-product-index-registries-dtr-1.0.html"><span class="tdh_035"><i><u>XBRL Data Type Registry 1.x</u></i></span></a>.</p>  

<p class="tdh_070"><b>debit </b>— A value for the balance type property of a concept such that, in accounting, this concept represents a debit or a monetary amount owed or paid.</p>  

<p class="tdh_070"><b>decimal</b> — A number that has both a whole number and a fractional component. This is also the XML data type for representing fractional numbers.</p>  

<p class="tdh_070"><b>decimals property</b> — The specified precision with which consumers should process a numeric fact. See the <a href="https://www.xbrl.org/WGN/precision-decimals-units/WGN-2017-01-11/precision-decimals-units-WGN-2017-01-11.html"><span class="tdh_035"><i><u>XBRL Precision, Decimals and Units 1.0</u></i></span></a> specification for more information.</p>  

<p class="tdh_070"><b>default</b> — An expected condition where none is specified.</p>  

<p class="tdh_070"><b>definition</b> <i>or</i> <b>definition relationship</b> — A relationship that arranges pairs of concepts in a specific semantic relationship. These relationships may be above and beyond calculation or presentation relationships. Concept core dimensions cannot be used in a definition relationship.</p>  

<p class="tdh_070"><b>definition linkbase</b> — An optional XML file containing additional relationships between concepts.</p>  

<p class="tdh_070"><b>dependent dimensions </b>— Data dimensions whose values rely upon the values of another dimension. Dependent dimensions cannot establish uniqueness within a data set. XBRL inherently does not permit the use of dependent dimensions as taxonomy-defined dimensions.</p>  

<p class="tdh_070"><b>dimension</b> — A data dimension is an axis intersecting or defining data points. XBRL constructs used to express data dimensionality are termed XBRL dimensions and are either core dimensions or taxonomy-defined dimensions.</p>  

<p class="tdh_070"><b>dimension-default</b> — A definition relationship indicating a concept is the default value for a taxonomy-defined dimension.</p>  

<p class="tdh_070"><b>dimension-domain</b> — A definition relationship indicating a concept represents the domain of a taxonomy-defined dimension.</p>  

<p><!-- Field: Page; Sequence: 170 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->155<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_070"><b>Discoverable Taxonomy Set</b> — A set of all linkbase and schema documents referenced within a taxonomy. The Discoverable Taxonomy Set (DTS) allows taxonomy developers to define all documents and linkbases required for the taxonomy.</p>  

<p class="tdh_070"><b>documentation</b> — A set of explanatory guides to aid readers in understanding and using an XBRL taxonomy. There can be numerous different types of documentation available to readers in either print or electronic form. Documentation needs vary by taxonomy size and complexity.</p>  

<p class="tdh_070"><b>domain</b> — A set of allowable values. In XBRL, a domain refers to an abstract concept that represents an entire set of other concepts for explicitly defined domains or whose data type represents the entire domain for the dimension (a typed domain). The domain and its members are used to classify facts along the axis. For example, &#8220;Arkansas&#8221; is a domain member in the domain &#8220;States&#8221; and would be used to classify elements such as revenues and assets in Arkansas as distinct from other states.</p>  

<p class="tdh_070"><b>domain-member </b>— A definition relationship indicating one concept is a member of the domain of the other concept, which is part of a taxonomy-defined dimension.</p>  

<p class="tdh_070"><b>draft taxonomy</b> — A version of the taxonomy that has passed internal changes and validation and is now ready for public review. Given comments from the public review and how they are addressed, the taxonomy can either return to a candidate stage or be implemented as a release taxonomy.</p>  

<p class="tdh_070"><b>duration</b> — A value for the period type property of a concept core dimension or a type of period core dimension that indicates the reported fact is relevant to a time period. If a concept core dimension&#8217;s period type is duration, that concept must intersect with a duration-type period core dimension.</p>  

<p class="tdh_070"><b>element</b> — A specific tag in XML. For XML based XBRL instance data, the element name with its associated namespace represents the concept core dimension applied to the contained fact data. For XBRL in XML and Inline XBRL, the terms element and concept are used interchangeably.</p>  

<p class="tdh_070"><b>encoding </b>— Encoding is the method of representing characters and character positions. The simplest encoding mode is ASCII (96 printable US-EN characters). Unicode represents more than 65 thousand character. Unicode Transformation Format (UTF) allows Unicode to be represented in an 8-bit wide channel or data store. XML, by default uses UTF encoding, but some systems are limited to accepting only ASCII. In HTML and XML, extended characters can also be represented as c<i>haracter entities</i> for example, &amp;#8224; is a Unicode dagger &#8220;†&#8221;.</p>  

<p class="tdh_070"><b>entity</b> — A business, department, school, group, or individual functioning as a data reporter. Generally, entities have some specific identifier, such as a tax number, LEI, or CIK number, that can be used in an XBRL report with the entity core dimension. Entity identifiers are required when combining instance data for comparison to separate reporters. Note that a reporting entity may not be the report preparer.</p>  

<p class="tdh_070"><b>entity core dimension</b> — A required XBRL dimension that identifies the entity.</p>  

<p class="tdh_070"><b>entry point</b> — A specific top-level default presentation or subset within a taxonomy. Taxonomies will often provide multiple entry points for different reporting purposes and use cases. There should be an entry point to define an entire taxonomy.</p>  

<p class="tdh_070"><b>essence-alias </b>— A definition relationship indicating one concept of a pair essentially has the same meaning as the other concept.</p>  

<p class="tdh_070"><b>explicit taxonomy-defined dimension</b> — A taxonomy-defined dimension whose domain of allowable values is explicitly enumerated within the taxonomy. Explicit taxonomy-defined dimensions have member concepts that represent allowable values for a domain. If extensibility is allowed, preparers may be able to add further domain member concepts.</p>  

<p class="tdh_070"><b>extensibility</b> — The ability of a taxonomy to allow custom, or user-defined, XBRL constructs. For an open, extensible taxonomy, this can involve extension labels, footnotes, concepts, dimensions, presentations, data types, or even incorporating entire extension taxonomies. Extensibility can increase user flexibility but decrease comparability among XBRL reports.</p>  

<p><!-- Field: Page; Sequence: 171 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->156<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_070"><b>extension </b><i>or </i><b>extension taxonomy </b>— A published, existing set of concepts which another taxonomy can include. In an open taxonomy, preparers can define their own concepts to extend one or more existing taxonomies. An extension taxonomy will have a unique namespace separating the concept names from the base taxonomy.</p>  

<p class="tdh_070"><b>fact</b> — A unique and discrete piece of information within an XBRL report as defined by the intersection of various XBRL dimensions. When all dimensions are defined correctly, a fact will not only be unique within the report but also globally amongst all data. The content of fact is dictated by the data type of its concept core dimension.</p>  

<p class="tdh_070"><b>fixed </b><i>or</i> <b>floating point</b> — A description of arithmetic approaches to representing fractional numbers in terms of bits while balancing range and precision. For XBRL, numeric values are defined by the concept core dimension&#8217;s data type, as well as the precision and decimals properties of the fact. See <i>decimals</i> and <i>precision</i>.</p>  

<p class="tdh_070"><b>footnote</b> <i>or</i> <b>note</b> — A footnote is used to add additional explanatory information to one or more facts. A footnote is added to a fact through the note core ID dimension. Note that footnotes and the note core ID dimension can add the same context to multiple facts and therefore cannot confer uniqueness.</p>  

<p class="tdh_070"><b>formula</b> — A mathematical relationship between two or more concepts. Note formulas are separate from calculations and can represent more complicated relationships.</p>  

<p class="tdh_070"><b>formula linkbase</b> — An optional XML file containing the formula relationships between concepts provided with an instance.</p>  

<p class="tdh_070"><b>functional requirement</b> — A specification of operations of a system or its components as a furtherance of what that system is meant to accomplish. Functional requirements may involve technical details, data manipulation and processing, calculations, and data modeling.</p>  

<p class="tdh_070"><b>general-special </b>— A definition relationship indicating one concept of a pair is a more specialized form of the other concept.</p>  

<p class="tdh_070"><b>governance</b> — The act of overseeing the creation, testing, implementation, support, and maintenance of a taxonomy or a structured reporting environment. A governance system sees a taxonomy through its lifecycle and may be comprised of one or more taxonomy working groups and committees.</p>  

<p class="tdh_070"><b>hierarchy</b> — A structuring of data such that items are ranked in relation to other items. A position within a hierarchy is considered a node, and the highest node (to which all other nodes are subordinate) is considered the root. Hierarchies make use of parent/child and sibling relationships between and among nodes. In XBRL, hierarchies are comprised of concept trees (presentation, calculation, and so forth) and are used to express and navigate concept relationships.</p>  

<p class="tdh_070"><b>human-readability</b> — The ability of humans to read and digest information presented in a report. Aside from reports submitted in Inline XBRL, XBRL reports are generally not considered human-readable.</p>  

<p class="tdh_070"><b>hypercube</b> — A multi-dimensional structure (cube) having more than three data planes. Most XBRL facts involve a hypercube structure.</p>  

<p class="tdh_070"><b>identifier</b> — A set of characters or digits that serves to uniquely identify an entity. Examples of identifiers include legal entity identifiers, social security numbers, central key index numbers, and tax ID numbers. Developers should use care in selecting identifiers that are publicly known.</p>  

<p class="tdh_070"><b>implementation phase</b> — The stage of the taxonomy lifecycle during which the taxonomy is implemented in the reporting environment.</p>  

<p class="tdh_070"><b>imputed value</b> — A value that is not specifically provided but could be calculated based on other provided numbers and calculation weights.</p>  

<p><!-- Field: Page; Sequence: 172 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->157<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_070"><b>information supply chain</b> — A system of organizations, people, activities, and resources involved in moving data from preparers to consumers. In this document, the supply chain refers specifically to data moving from the preparer&#8217;s business data model to a consumer&#8217;s model via the transport model (or the XBRL taxonomy).</p>  

<p class="tdh_070"><b>independent dimensions </b>— Data dimensions whose values so not rely upon the values of another dimension. Independent dimensions within a data set are often said to be orthogonal to one another.</p>  

<p class="tdh_070"><b>inheritance</b> — The act of assuming the properties or characteristics of a parent item or element. Hierarchical relationships in XBRL do not imply inheritance.</p>  

<p class="tdh_070"><b>inline XBRL</b> — An XBRL transport format that embeds XBRL tagging directly into an XHTML document. This produces a single human-readable and machine-readable document.</p>  

<p class="tdh_070"><b>instance</b> <i>o</i>r <b>instance document </b>— A file that contains one instance business reporting information using one or more XBRL taxonomies. The instance document (or XBRL report) represents a collection of facts and report-specific information.</p>  

<p class="tdh_070"><b>instant</b> — A value for the period type property of a concept core dimension or a type of period core dimension that indicates the reported fact is relevant to a particular point in time. If a concept core dimension&#8217;s period type is instant, that concept must intersect with an instant-type period core dimension</p>  

<p class="tdh_070"><b>intellectual property agreement</b> — A legal document specifying that ideas and work contributed to a project has been freely provided and not eligible for a creative property claim.</p>  

<p class="tdh_070"><b>integer</b> — A data type indicating that the fact is stated in whole numbers.</p>  

<p class="tdh_070"><b>javascript object notation (JSON)</b> — A text format that provides for the expression of complex structured data through parameter:value pairs. A number of programming languages will natively create and read JSON.</p>  

<p class="tdh_070"><b>key</b> — A set of values in a combination of data dimensions that serves to uniquely identify a data point.</p>  

<p class="tdh_070"><b>label</b> — A human-readable name for a concept. Each concept has a standard label that corresponds to the concept name and is unique across the taxonomy. Other labels can also be applied.</p>  

<p class="tdh_070"><b>label linkbase</b> — An optional XML file containing information to associate labels to concepts.</p>  

<p class="tdh_070"><b>label role</b> — A distinguishing name for each distinct concept indicating the circumstances in which it should be used. Each concept may be given a separate defining label role to use in different presentation situations.</p>  

<p class="tdh_070"><b>language core dimension </b>— An optional XBRL dimension that identifies the language of a textual fact.</p>  

<p class="tdh_070"><b>lifecycle</b> — The stages of taxonomy development, validation, implementation, and maintenance. The size and complexity of the taxonomy and the reporting requirements should dictate the level of governance required to oversee the taxonomy lifecycle.</p>  

<p class="tdh_070"><b>line item</b> — An element that conventionally appears on the vertical axis (rows) of a table.</p>  

<p class="tdh_070"><b>linkbase</b> — An XML file containing information that defines relationships among the concepts of an XBRL taxonomy. Linkbase files end with a &#8220;.xml&#8221; file extension. Some types of linkbase files are optional.</p>  

<p class="tdh_070"><b>logical data model</b> — A model that defines the data points in the conceptual data model and how they relate to each other and other data constructs.</p>  

<p class="tdh_070"><b>machine-readability</b> — The ability of computers to read and parse information presented in a report. XBRL reports are formatted in a structured, pre-determined manner and are thus designed to be machine-readable.</p>  

<p><!-- Field: Page; Sequence: 173 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->158<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_070"><b>many-to-many relationship</b> — A data dimension where many data points are related to many other data points.</p>  

<p class="tdh_070"><b>minimum data set</b> — The amount of data necessary to meet all the use cases, requirements, and regulations involved in a taxonomy without including redundant or extraneous information.</p>  

<p class="tdh_070"><b>namespace</b> — A Universal Resource Identifier (URI) identifying the organization that maintains the concept definitions. Namespaces are used to identify specific taxonomy components that make up an entire set of data. Namespaces are usually shortened a namespace prefix, which then becomes part of a qualified name (qname). Many prefix names are conventionally used, such as &#8220;ix&#8221; for Inline XBRL or &#8220;us-gaap&#8221; for the US GAAP taxonomy. Namespaces are used both within XML as part of the element name and also as part of XBRL to identify taxonomies.</p>  

<p class="tdh_070"><b>negating label</b> — A label type that causes numeric values of a concept to be displayed with their sign flipped.</p>  

<p class="tdh_070"><b>nillable</b> — A concept property that indicates if the fact intersecting with that concept can be empty (nil or not reported). If the nillable property is &#8220;false&#8221;, the fact must have a non-empty value. XBRL taxonomy tools normally have the default value for nillable as &#8220;true&#8221;. Note that nil is not synonymous with a value of zero.</p>  

<p class="tdh_070"><b>node</b> — A position in a hierarchy.</p>  

<p class="tdh_070"><b>non-functional requirement</b> — A requirement that imposes a constraint on the system&#8217;s design or implementation, quite often for quality or ease-of-use purposes. Non-functional requirements may be posed as requests/recommendations and must be weighed carefully in terms of their cost versus their benefit and their impact on the overall taxonomy.</p>  

<p class="tdh_070"><b>non-numeric data</b> — Data that is not quantifiable. In XBRL, non-numeric data is quite commonly text. Non-numeric data cannot be used in mathematical operations.</p>  

<p class="tdh_070"><b>non-relational data</b> — A data set that has no semantic relationships among its data points.</p>  

<p class="tdh_070"><b>note core ID dimension</b> — An optional XBRL dimension that links one or more XBRL facts to footnote data through a unique ID number specific to that footnote or set of footnotes.</p>  

<p class="tdh_070"><b>numeric data</b> — Data that is quantifiable, measurable, and can be expressed with solely numerals. Numeric data can be used in mathematical operations.</p>  

<p class="tdh_070"><b>one-to-many relationship</b> — A data dimension where one data point is related to many other data points.</p>  

<p class="tdh_070"><b>one-to-one relationship</b> — A data dimension where one data point is related to one other data point.</p>  

<p class="tdh_070"><b>ontology</b> — <span class="tdh_036">A set of concepts in a subject area or domain showing the properties of those concepts and the relationships between them. An ontology is commonly referred to as a taxonomy.</span></p>  

<p class="tdh_070"><b>open property</b> — A property of a hypercube that specifies that any of the taxonomy-defined dimensions in the hypercube can intersect on a fact in order for that fact to be part of the hypercube.</p>  

<p class="tdh_070"><b>parent/child relationship</b> — A relationship between concepts that indicates subordination of one concept to the other in a hierarchy. Linkbase files often use parent/child hierarchies to model several different relationships, including presentations, calculations, and membership of concepts within a domain used as the axis of a table. Note there is no inheritance of values or properties implied by the parent/child relationship in XBRL.</p>  

<p class="tdh_070"><b>period core dimension </b>— A required XBRL dimension that identifies the time period relevant to a fact. A period core dimension can either be instant or duration.</p>  

<p><!-- Field: Page; Sequence: 174 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->159<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_070"><b>period type</b> — A property of a concept that reflects whether it is reported for an instant or duration time period. The period type indicates the type of period core dimension (instant or duration) with which the concept core dimension may intersect.</p>  

<p class="tdh_070"><b>physical data model</b> — A physical data model includes all the concepts of the taxonomy, including their properties, as well as the relationships among the concepts (as arcs or through an abstract hierarchical structure for example).</p>  

<p class="tdh_070"><b>pilot</b> <i>or</i> <b>candidate taxonomy</b> — A version of a taxonomy set forth for testing and validation. Once the taxonomy has been validated to internal standards, the pilot or candidate version becomes a draft taxonomy set for public review.</p>  

<p class="tdh_070"><b>pilot phase</b> — The stage of the taxonomy lifecycle during which the taxonomy is validated and opened to public review. Changes to the candidate and draft taxonomies should be incorporated before an official release.</p>  

<p class="tdh_070"><b>precision</b> — The specified level of numeric precision with which a consumer should process a numeric fact. See the <a href="https://www.xbrl.org/WGN/precision-decimals-units/WGN-2017-01-11/precision-decimals-units-WGN-2017-01-11.html"><span class="tdh_035"><i><u>XBRL Precision, Decimals and Units 1.0</u></i></span></a> specification for more information.</p>  

<p class="tdh_070"><b>prefix</b> <i>or</i> <b>namespace prefix</b> — A shorthand sequence of letters for a namespace (for example, &#8220;US GAAP&#8221; is a common prefix for the namespace <a href="http://xbrl.us/US%20GAAP/2008-01-31"><span class="tdh_035"><i><u>http://xbrl.us/US GAAP/2008-01-31</u></i></span></a>). The prefix precedes a concept name and indicates to which namespace that concept belongs. See <i>namespace</i> and <i>qname</i>.</p>  

<p class="tdh_070"><b>preparer </b>— The party or parties that produce XBRL instance (and linkbase) data. Preparers can include, but are not limited to, companies, filing agents preparing XBRL reports on the behalf of others, and other industry reporters.</p>  

<p class="tdh_070"><b><i>Preparer Guide</i></b> — A document detailing how to use the taxonomy to produce XBRL reports. The <i>Preparer Guide</i> should cover data preparation, transformation, validation, and dissemination as applicable. Supporting software systems should be documented as well.</p>  

<p class="tdh_070"><b>presentation </b><i>or</i> <b>presentation relationship</b> — A relationship that arranges concepts in a hierarchy. Presentations often group concepts by semantic similarity or common use case.</p>  

<p class="tdh_070"><b>presentation linkbase</b> — An XML file containing information to link concepts together in a presentation structure. The presentation linkbase defines the organizational relationships of concepts using parent/child hierarchies.</p>  

<p class="tdh_070"><b>project scope </b>— The work that must be done to deliver a product with a predetermined set of features and functions.</p>  

<p class="tdh_070"><b>public review </b>— The opportunity for the public (which may vary given the size and impact of the taxonomy) to comment on and suggest changes for a candidate/pilot XBRL taxonomy. Public reviews generally last for a pre-determined amount of time before the suggestions are gathered, evaluated, and changes are made if warranted in a new draft taxonomy.</p>  

<p class="tdh_070"><b>qname</b> — A qualified XML name with both a namespace prefix and the concept (element) name (for example, &#8220;ix:nonFraction&#8221; or &#8220;us-gaap:CashAndCashEquivalents&#8221; are qualified names).</p>  

<p class="tdh_070"><b>reference</b> — Information that adds sources, interpretations, and other important industry-based context to a concept. See <i>authoritative reference</i>.</p>  

<p class="tdh_070"><b>reference linkbase</b> — An optional XML file containing information to provide authoritative literature (references) for concepts.</p>  

<p class="tdh_070"><b>regulatory or NGO requirements</b> — The rules, mandates, or stipulations to which data represented by an XBRL must adhere. These types of requirements may come from governmental agencies, non-governmental organizations, industry groups, or internal oversight within the industry. They are often a</p>  

<p><!-- Field: Page; Sequence: 175 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->160<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_070">large, driving force in determining the taxonomy&#8217;s functional requirements, and preparers typically must be in compliance with these requirements when they prepare an XBRL report.</p>  

<p class="tdh_070"><b>relational data</b> — A data set that has one or more semantic relationships among its data points. XBRL is designed to represent relational data.</p>  

<p class="tdh_070"><b>render or rendering</b> — The processing of displaying a taxonomy or an instance document in a layout that facilitates readability and understanding of its contents. XBRL software is typically required for rendering.</p>  

<p class="tdh_070"><b>reporting entity</b> — An entity reporting data (synonymous with entity).</p>  

<p class="tdh_070"><b>requires-element </b>— A definition relationship indicating the value of one concept is required should the value of the other concept in the pair be present.</p>  

<p class="tdh_070"><b>root</b> — The top node of a hierarchical tree. The root can appear only once in that tree.</p>  

<p class="tdh_070"><b>scaling</b> — A process that automatically scales numeric data by a defined value.</p>  

<p class="tdh_070"><b>scenario</b> — An XBRL construct that allows for additional information to be associated with facts in an instance document. This information encompasses the reporting circumstances of that fact (for example, &#8220;actual&#8221; or &#8220;forecast&#8221; describe contextual reporting circumstances). The scenario of any fact can be left unspecified. Scenarios can only be used in XBRL as XML or Inline XBRL.</p>  

<p class="tdh_070"><b>schema</b> — An XML file that defines the elements, structure, and data types of another XML file. XBRL schemas only define the concepts and data types; linkbases contain the structural information and relationships among the concepts. Schema files end with a &#8220;.xsd&#8221; file extension. A schema file can include and/or reference multiple other schema and linkbase files.</p>  

<p class="tdh_070"><b>segment</b> — An XBRL construct that allows additional information to be included in the context of an instance document. This information captures information such as an entity&#8217;s business units, type of debt, type of other income, and so forth. The scenario of any fact can be left unspecified. Scenarios can only be used in XBRL as XML or Inline XBRL.</p>  

<p class="tdh_070"><b>semantic data model </b>— A model that structures data in a specific, logical way. A semantic data model adds basic semantic and/or qualitative meaning to data points and the relationships that lie between them.</p>  

<p class="tdh_070"><b>semantic interoperability </b>— A data structure that is interpreted by the receiving system with all the meaning required to interpret that data, regardless of the originating system, time of interpretation, or the method of transmission. Semantic interoperability is achieved through adding information that links each data element to a well-defined, shared vocabulary among the systems.</p>  

<p class="tdh_070"><b>sibling relationship</b> — A relationship between concepts that indicates two or more concepts have the same parent concept (are located at the same level in hierarchy).</p>  

<p class="tdh_070"><b>similar-tuples </b>— A definition relationship that is operationally the same as the essence-alias definition but reserved for usage with tuples. Tuples are not commonly used.</p>  

<p class="tdh_070"><b>specification</b> — An industry-developed set of precise precepts and instructions for creating a technical document. XBRL has multiple specifications that underlie and define its usage, include the <a href="https://specifications.xbrl.org/work-product-index-group-base-spec-base-spec.html"><span class="tdh_035"><i><u>XBRL Specification</u></i></span></a>, the <a href="https://specifications.xbrl.org/work-product-index-group-dimensions-dimensions.html"><span class="tdh_035"><i><u>XBRL Dimensions Specification</u></i></span></a>, and the <a href="https://specifications.xbrl.org/work-product-index-open-information-model-open-information-model.html"><span class="tdh_035"><i><u>XBRL Open Information Model</u></i></span></a>.</p>  

<p class="tdh_070"><b>stakeholder</b> — An entity with interest or concern in a project. A stakeholder may be comprised of a single person, a group of people, or an entire organization. In XBRL taxonomy development, stakeholders typically offer opinions, insight, and experience concerning the nature of the data to be reported and how that reporting process should operate.</p>  

<p class="tdh_070"><b>standard label</b> — The default label for a concept. An extension may override the standard label.</p>  

<p><!-- Field: Page; Sequence: 176 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->161<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_070"><b>substitution group property</b> — A property of a concept categorizing that concept as one of a number of types, such as item, dimension, or hypercube.</p>  

<p class="tdh_070"><b>suffix </b>— An ending to a concept name that specifies that concept&#8217;s role in the taxonomy (&#8220;Axis,&#8221; &#8220;Table,&#8221; or &#8220;Member&#8221;, for example). Abstract concepts are often named with a suffix.</p>  

<p class="tdh_070"><b>support and maintenance phase </b>— The stage of the taxonomy lifecycle during which the taxonomy is regularly updated to reflect new or altered regulatory requirements, technological updates, or other changes. Changes must be disseminated to the reporting environment.</p>  

<p class="tdh_070"><b>syntactic interoperability</b> — A common syntax by which two or more systems communicate with each other. XBRL provides for syntactic interoperability through a syntactical specification that relies on XML and a means of providing an ontology (an XBRL taxonomy) to identify the meaning of that information within a well-defined semantic framework.</p>  

<p class="tdh_070"><b>table</b> — A method of organizing relational data along a set of dimensions (columns) and a set of line items (rows). In XBRL, each fact of one of the line items can be further characterized along one or more of its dimensions.</p>  

<p class="tdh_070"><b>tag </b>— Markup information that describes an XBRL fact in an instance document expressed in XML or Inline XBRL. Angle brackets (&#8220;&lt;&gt;&#8221; and &#8220;&lt;/&gt;&#8221;) enclose tags around XBRL facts.</p>  

<p class="tdh_070"><b>taxonomy</b> — An electronic library of XBRL concepts used to report data, describing both those concepts&#8217; semantic meanings and their relationships with each other. A taxonomy is composed of a schema file (.xsd) and linkbase files (.xml) directly referenced by that schema. An XBRL taxonomy can be considered a transport data model or the structured model by which information is transferred from a source business model to a data consumer model.</p>  

<p class="tdh_070"><b>taxonomy committee</b> — A combination governance structure of the taxonomy steering committee and the taxonomy working group. This setup is well suited for the support and maintenance phase of taxonomy development or for taxonomies that are smaller in size and scope.</p>  

<p class="tdh_070"><b>taxonomy-defined dimension </b>— An optional XBRL dimension that expresses additional contextual and semantic information about a fact. Taxonomy-defined dimensions are comprised of abstract concepts and can be either explicit or typed. Taxonomy-defined dimensions are defined with a combination of the taxonomy schema file and one or more linkbase files.</p>  

<p class="tdh_070"><b><i>Taxonomy Guide</i></b> — A document explaining the nature of the XBRL taxonomy, including the design decisions that went into its creation, to an audience of developers. The <i>Taxonomy Guide</i> should contain an in-depth discussion of the taxonomy itself, its structure, validation methods, and other relevant information that aids developers in understanding how the taxonomy functions as a data transport model.</p>  

<div class="tdh_066"><b>taxonomy manager</b> — The individual(s) functioning as a point of contact for all stages of the taxonomy lifecycle. The taxonomy manager maintains detailed knowledge of the taxonomy and the project as a whole and provides day-to-day staff support for the taxonomy working group, as well as receiving and reviewing comments, overseeing and testing changes, and coordinating with regulators or other stakeholders.</div>
<p class="tdh_070"><b>taxonomy sponsor</b> — The individual, group, or organization championing the development of the XBRL taxonomy. For large taxonomies with a wide impact on the information supply chain, a regulator, standards organization, or non-profit industry body may act as sponsor to successfully bring together stakeholders. For small taxonomies, the sponsor may be internal to a company.</p>  

<div class="tdh_066"><b>taxonomy steering committee </b>— The group overseeing the development of the taxonomy during the build and pilot phases. This group can be comprised of technical and subject matter experts, and it can evaluate the major milestones, reviews and approves taxonomy deliverables, and serve as a &#8220;tie breaker&#8221; on major decisions. A taxonomy steering committee is often applicable to a large taxonomy development project.</div>
<p><!-- Field: Page; Sequence: 177 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->162<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div class="tdh_066"><b>taxonomy working group</b> — The group conducting and implementing the development of the taxonomy during the build, pilot, and implementation phases. This group may include preparers, data intermediaries, and data consumers, as well as software and database providers and taxonomy developers. Regulators, legislators, and industry experts can serve as observers to ensure legislative requirements and regulatory goals are correctly implemented.</div>
<p class="tdh_070"><b>transformation</b> — An Inline XBRL construct that describes how the descriptive language can be converted to an appropriate XBRL format. For more information, see the <a href="https://specifications.xbrl.org/work-product-index-inline-xbrl-transformation-registry-3.html"><span class="tdh_035"><i><u>XBRL Transformation Registry</u></i></span></a>.</p>  

<p class="tdh_070"><b>transport data model</b> — A semantic data model intended to organize and transport data from a business data model to a consumer data model. An XBRL taxonomy, which is highly structured and standardized, serves as a machine-readable transport model.</p>  

<p class="tdh_070"><b>tree</b> — The common name for the visual display of a hierarchy, with a root node, branching nodes, and further child nodes.</p>  

<p class="tdh_070"><b>tuple</b> — A method of expressing an XBRL fact such that the fact is comprised of two or more data point pairs. Tuples are rarely used in XBRL taxonomies.</p>  

<p class="tdh_070"><b>typed taxonomy-defined dimension</b> — A taxonomy-defined dimension whose domain of allowable values is determined by the data type of its domain concept. This data type can be loose or tightly constrained, and it can contain an enumeration of allowable values.</p>  

<p class="tdh_070"><b>unit </b>— The units in which numeric items have been measured, such as dollars, watts, pounds, or Euros per share.</p>  

<p class="tdh_070"><b>unit core dimension </b>— An optional XBRL dimension that expresses the units of a fact. The unit core dimension is only applicable to numeric facts.</p>  

<p class="tdh_070"><b>usable property</b> — A property of a domain value that means this value is permissible in a hypercube.</p>  

<p class="tdh_070"><b>use case</b> — A type of requirements specification for a system that represents a list of actions or steps that defines interactions between users and the system to achieve a specific goal.</p>  

<div class="tdh_066"><b>UTF-8</b> — A method of encoding Unicode characters. <span class="tdh_001">UTF-8 is a variable width character encoding capable of encoding all 1,112,064 valid code points in Unicode using one to four 8-bit bytes. XML is typically encoded in UTF-8. See <i>encoding</i>.</span></div>
<p class="tdh_070"><b>validation</b> — The process of checking that instance documents and taxonomies correctly meet the rules of the XBRL specification, any regulatory requirements, or other requirements set forth by the taxonomy developers.</p>  

<p class="tdh_070"><b>weight</b> — A calculation relationship attribute (-1 or +1) that works in conjunction with parent and child numeric concepts to determine the arithmetic summation relationship between them.</p>  

<p class="tdh_070"><b>white paper </b>— A short document that concisely presents an industry problem, the pertinent regulations, requirements, and use cases relevant to the problem, the options considered, and an XBRL taxonomy as a solution.</p>  

<p class="tdh_070"><b>workflow</b> — The sequence of development, administrative, validation, implementation, or other processes through which a piece of work passes from initiation to completion.</p>  

<p class="tdh_070"><b>XBRL</b> — Extensible Business Reporting Language, or an XML-based standard for electronic communication of financial and business data that provides for both machine and human-readability.</p>  

<p class="tdh_054"><b>XBRL dimension</b> — An XBRL construct that serves to add semantic information to a fact. XBRL dimensions also uniquely identify a fact. An XBRL dimension may either be one of the core dimensions listed below or a taxonomy-defined dimension.</p>  

<p class="tdh_072">Concept Core Dimension* Period Core Dimension* Entity Core Dimension*</p>  

<p><!-- Field: Page; Sequence: 178 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->163<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<p class="tdh_072">Language Core Dimension Unit Core Dimension Note ID Core Dimension</p>  

<p class="tdh_055">Taxonomy-Defined Dimension</p>  

<p class="tdh_070">Items marked with an asterisk (*) are required on any given fact.</p>  

<p class="tdh_070"><b>XML</b> — Extensible Markup Language, which is used to describe and define data by allowing users to define their own elements (in contrast to HTML where the tags are predefined). XBRL is an XML-based standard.</p>  

<p class="tdh_070"><b>zero-to-many relationship</b> — A data dimension where one data point can exist with or without many other data points.</p>  

<p class="tdh_070"><b>zero-to-one relationship</b> — A data dimension where one data point can exist with or without the other data point of a pair.</p>  

<p><!-- Field: Page; Sequence: 179 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->164<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt; float: right; margin: 8px; border: 1px solid #e2e2e2; border-bottom: none;"><a href="#toc">Table of Contents</a></div>
<p class="tdh_030"><a name="a_Toc24107590"></a><a name="a_Toc23337736"></a>Index</p>  

<table class="tdh_238" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">A</td>
</tr>
<tr class="tdh_197">
<td class="tdh_262">abstract property, 24, 33, 47, 48, 52, <b>85</b></td>
<td class="tdh_245"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">arc, 33</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">arcrole, 55</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">Arelle, 11, 34, 81, 83, 89–91</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">file type, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">file/HREF/role definition, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195"><i>Load from Excel</i> plugin, 89</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">namespace URI, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">prefix/type, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">specification, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">attribute</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XML, 25</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">authoritative reference, 35</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">axis. See dimension</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">B</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">balance type property, 24, 53, <b>85</b></td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">credit, 24, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">debit, 24, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">business data model, 13, 95</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">C</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">calculation, 31, 34, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">defining concept weight, 86</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">defining parent concept, 86</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 96, 101</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">example, 54</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension calculations, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">linkbase, 34</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">camel case, 25</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">candidate taxonomy. <i>See</i> pilot taxonomy</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">closed property, 35, 55</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">closed taxonomy, 55, 116</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">colheader specification, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">comparability</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">impact of extensibility, 78–80</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL reports, 78</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">concept, 5, 22–25, 52</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">abstract, 24, 31, 32, 33, 47, 49, 52, <b>85</b></td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">balance type, 24, <b>85</b></td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">core dimension, 46, <i>See</i> concept core dimension</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">cross-usage, 97</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">data type, 24, 29, 52, 53, 72, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">depth, 32, 34, 86</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 96, 100, 105</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">in a hierarchy, 31</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">label, 25</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">name, 24, 25, 32, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">nillable, 24, 52, <b>85</b></td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">period type, 24, 52, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">prefix, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">property, 23–25, 32, 52, 75, 83, 96</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">spreadsheet template, 83–87</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">substitution group, 24, 32, 33, 52, 53, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">suffix, 32, 49, 53</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">concept core dimension, 19, 20, 41, 46, 47, 52, 73</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension concept, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">concept grouping, 22, 31</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">concept naming</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">camel case, 25</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">conceptual data model, 69</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">consumer, 59, 61, 62, 65, 95</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195"><i>Data Consumer Guide</i>, <i>92</i>, 103</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">consumer data model, 13</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">context, 55</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XML, 27</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">credit</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a balance type value, 24, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">CSV, 69</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a data format, 14, 78</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">validation, 81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">cube. See hypercube</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">D</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194"><i>Data Consumer Guide</i>, <i>92</i>, 103–107</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">data model, 38–40</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">business model, 13, 60</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">conceptual model, 69</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">consumer model, 13, 60</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">hierarchy, 15, 31</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">logical, 70</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">logical model, 69</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">non-relational data, 37</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">physical model, 71</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">relational data, 38–40</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">semantic model, 13</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">transport model, 13, 67–77</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">data point, 15, 37</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">uniqueness, 37, 71, 74</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">unit, 21</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">data quality</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 102</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">data quality committee, 80, 110</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">data set</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">minimum, 68</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">preparation, 99</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">data type, 29, 47, 72</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a concept property, 24, 52, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a means of validation, 81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 97, 101</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension data type, 80</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">non-numeric, 29</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">numeric, 29</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">data type property, 24, 52</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">debit</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a balance type value, 24, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">decimals property, 26, 30</td>
<td class="tdh_199"></td>
</tr>
</tbody>
</table>
<p><!-- Field: Page; Sequence: 180 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->165<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<table class="tdh_238" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_197">
<td class="tdh_265">definition, 31, 35, 50</td>
<td class="tdh_236"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">dimension-default, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">dimension-domain, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 101</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">domain-member, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">essence-alias, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">example, 54</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension definitions, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">general-special, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">linkbase, 35</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">requires-element, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">similar-tuples, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">dependent dimensions, 39</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">in XBRL, 43–46</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">depth. <i>See</i> concept depth</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">dimension</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">arbitrary, 45</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">creating uniqueness, 37</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">dependent dimensions, 39</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 96</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">independent dimensions, 38</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">taxonomy-defined. See taxonomy-defined dimension</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL dimension. <i>See</i> XBRL dimension</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">dimension-default relationship, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">dimension-domain relationship, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">dimensionItem</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a substitution group value, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">Discoverable Taxonomy Set, 10, 32</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">file/HREF/role definition, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">namespace URI, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">prefix/type, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">specification, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">spreadsheet template, 87–89</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">documentation, 64, 92</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195"><i>Data Consumer Guide</i>, <i>92</i>, 103–107</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195"><i>Preparer Guide</i>, <i>92</i>, 98–103</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195"><i>Taxonomy Guide</i>, <i>92</i>, <i>94</i>–<i>98</i></td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195"><i>Taxonomy White Paper</i>, <i>92</i>, <i>94</i></td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195"><i>XBRL Overview</i>, <i>93</i>, <i>94</i>, 99, 104</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">domain, 22</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">dimension-domain relationship, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">domain-member relationship, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">explicit taxonomy-defined dimension, 48, 74</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">domain-member relationship, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">draft taxonomy, 111</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">duration</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a period type. See period core dimension or period type property</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">E</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">element</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XML, 25, 83</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">encoding, 78</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">entity core dimension, 19, 21</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">entry point, 31</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">creating, 89</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 100</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">essence-alias relationship, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">explicit dimension</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extensibility, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">explicit XBRL dimension, 74, 96</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">extensibility, 33, 56–57, 58, 78–80, 112, 116</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">advantages and disadvantages, 56</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a feature of XBRL, 15</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">closed taxonomy, 55</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 101</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">explicit dimension, 75</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension calculations, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension concepts, 48, 56, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension data types, 56, 80</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension definitions, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension dimensions, 57</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension footnotes, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension labels, 57, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension presentations, 50, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension taxonomy, 57, 80</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">impact on comparability, 78</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">open taxonomy, 56</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">extension specification, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">F</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">fact, 5, 16–18</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">precision, 25, 30</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">property, 25</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">scaling, 25, 30</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">footnote, 29, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 101</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">formula, 54</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 96, 101</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">functional requirement, 59, 65, 68</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">G</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">general-special relationship, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">generate specification, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">governance, 63, 64, 108–113</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">data quality, 66</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">example, 116</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">impact of taxonomy changes, 112</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">H</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">hierarchy, 15, 71</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">defining, 86</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">in XBRL, 48</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">inheritance, 14, 32</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">node, 32</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">parent/child relationship, 32</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">sibling relationship, 32</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">human-readablility, 29</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">hypercube, 35, 53</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">closed, 35, 55</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">hypercubeItem, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">open, 35, 55</td>
<td class="tdh_199"></td>
</tr>
</tbody>
</table>
<p><!-- Field: Page; Sequence: 181 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->166<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<table class="tdh_238" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_197">
<td class="tdh_266">usable, 55</td>
<td class="tdh_236"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">hypercubeItem</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a substitution group value, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">I</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">identifier</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 101</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">legal entity identifier, 101</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">import specification, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">imputed value, 77</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">include specification, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">independent dimensions, 38</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">in XBRL, 42–43</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">information supply chain, 13, 60, 61</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">inheritance, 32</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">Inline XBRL, 15, 120</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a data format, 14, 27, 78</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">scaling, 30</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">transformation, 30</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL fact example, 28</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">instance document. See XBRL report</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">instant</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a period type. See period core dimension or period type property</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">intellectual property, 64</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">agreement, 64</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">item</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a substitution group value, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">J</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">JSON</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a data format, 14, 78</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">validation, 81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL fact example, 28</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">K</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">key</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">defining uniqueness, 37</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">L</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">label. <i>See</i> concept label</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 101</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension labels, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">negated, 34</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">preferred, 86</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">presentation, 84</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">standard, 84</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">terse, 84</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">verbose, 84</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">label linkbase, 35, 55</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">language core dimension, 19, 22, 47</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">lifecycle, 108–113</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">build phase, 109–110</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">implementation phase, 111</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">pilot phase, 110–111</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">support and maintenance phase, 112–113, 121</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">linkbase, 33–35, 64, 76</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">Arelle file type, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a means of validation, 81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">calculation, 34</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">definition, 35</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 97</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">file creation, 83</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">file extension, 89</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">formula, 35</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">label, 35</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">presentation, 33</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">reference, 35</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">specifying the type in Arelle, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">logical data model, 69, 70</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">M</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">machine-readability, 29</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">manager</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">for the taxonomy, 109</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">many-to-many relationship, 39, 70</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">member</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">explicit taxonomy-defined dimension, 48</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">meta specification, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">meta-data</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">specifying in Arelle, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">minimum data set, 68</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">N</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">namespace, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XML, 25</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">negated label, 34</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">nillable property, 24, 52, <b>85</b></td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">non-functional requirement, 59, 65, 68</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">non-numeric. See data type</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">non-relational data, 37</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">note core ID dimension, 29, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">numeric. See data type</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">O</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">one-to-many relationship, 39, 70</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">one-to-one relationship, 38, 70</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">ontology. See taxonomy</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">open property, 35, 55</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">open taxonomy, 56</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">P</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">parent/child relationship, 32, 49</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">calculation, 86</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">period core dimension, 19, 21</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">duration, 19, 21</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">instant, 19, 21</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">period type property, 24, 52, 85</td>
<td class="tdh_199"></td>
</tr>
</tbody>
</table>
<p><!-- Field: Page; Sequence: 182 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->167<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<table class="tdh_238" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_197">
<td class="tdh_266">duration, 24, 85</td>
<td class="tdh_236"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">instant, 24, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">physical data model, 71</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">pilot taxonomy, 109</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">preferred label, 86</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">prefix</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">schema, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">preparer, 59, 61, 62, 65, 95</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">burden, 121</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195"><i>Preparer Guide</i>, <i>92</i>, 98</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194"><i>Preparer Guide</i>, <i>92</i>, 98–103</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">presentation, 31, 33, 49–50, 76</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">adding presentations, 86</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">concept preferred label, 86</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 100</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">example, 54</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension presentations, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">linkbase, 33</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">naming in Arelle, 86</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">presentation label, 84</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">project scope, 58</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">public review, 91, 110</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">R</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">reference</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">authoritative, 35</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">formula, 35</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">linkbase, 35</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">reference linkbase, 55</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">regulator, 61, 65</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">regulatory requirement, 63, 117</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">governmental, 63</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">non-governmental, 63</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">validation, 63</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">regulatory requirements</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 102</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">relational data, 38–40, 69</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">many-to-many relationship, 39, 70</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">one-to-many relationship, 39, 43, 70</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">one-to-one relationship, 38, 43, 70</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">zero-to-many relationship, 70</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">zero-to-one relationship, 70</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">released taxonomy, 111</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">requirement</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">functional, 59, 65</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">non-functional, 59, 65, 68</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">regulatory, 63, 117</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">resource, 63</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">requires-element relationship, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">resource requirement, 63</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">role</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">Arelle file type, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">S</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">scaling</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">Inline XBRL, 30</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">scenario, 55</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">schema, 25, 33, 64</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">Arelle file type, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">file creation, 83</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">file extension, 89</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">prefix, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">segment</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XML, 27</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">semantic data model, 13, 31</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">semantic interoperability, 12</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">sibling relationship, 32</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">similar-tuples relationship, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">skip rows specification, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">software</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a means of validation, 81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">development, 63, 80, 111, 115</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documentation, 98</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">specification, 10</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">Extensible Business Reporting Language Specification, 10</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL Data Type Registry, 10</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL Dimensions, 10, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL Formula, 10</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL Open Information Model, 10</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL Precision, Decimals and Units, 10</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL Transformation Registry, 11, 30</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL Units Registry, 10, 21</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">sponsor</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a regulatory agency, 116, 120</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as an industry, 118</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">for the taxonomy, 109</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">spreadsheet tools, 82–91</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">Concepts Sheet, 83–87</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">Discoverable Taxonomy Set Sheet, 87–89</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">stakeholder, 61–62, 65, 109</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">consumer, 61, 65</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">preparer, 61, 65</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">regulator, 61, 65</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">standard label, 84</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">substitution group property, 24, 33, 52, 53, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">dimensionItem, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">hypercubeItem, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">item, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">suffix</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">concept, 32</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">suffix</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">concept, 32</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">syntactic interoperability, 12</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">syntactical specification, 12</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">systems</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">current, 69</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">legacy, 69</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">software, 63, 80</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">supporting, 62, 80</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">T</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">table</td>
<td class="tdh_199"></td>
</tr>
</tbody>
</table>
<p><!-- Field: Page; Sequence: 183 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->168<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<table class="tdh_238" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_197">
<td class="tdh_266">as a data structure, 22</td>
<td class="tdh_236"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">tag. <i>See</i> XML element</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">taxonomy</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">adoption and use, 92, 111, 119, 121</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a transport model, 13, 40–55, 60, 67–77</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">closed taxonomy, 55, 78</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195"><i>Data Consumer Guide</i>, <i>92</i>, 103–107</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 64, 92, <i>94</i>–<i>98</i>, 104</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">draft, 111</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension taxonomy, 57, 80</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">goal, 58</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">governance, 108–113</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">impact of changes, 112</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">lifecycle, 108–113</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">manager, 109</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">open taxonomy, 56, 78</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">overview, 6</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">pilot, 109</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">prefix, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195"><i>Preparer Guide</i>, <i>92</i>, 98–103</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">presentation, 76</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">reference, 97</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">released, 111</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">scope, 62</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">sponsor, 109</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">steering committee, 109</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">structure, 30–36, 95, 104</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">supporting systems, 62</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">taxonomy committee, 111</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195"><i>Taxonomy Guide</i>, <i>92</i>, <i>94</i>–<i>98</i></td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195"><i>Taxonomy White Paper</i>, <i>92</i>, <i>94</i></td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">workflow, 82</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">working group, 109</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL Overview, 104</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">taxonomy committee, 111</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">Taxonomy Development Template, 83</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">Taxonomy Guide, 58, <i>92</i>, <i>94</i>–<i>98</i></td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">taxonomy steering committee, 109</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194"><i>Taxonomy White Paper</i>, <i>92</i>, <i>94</i></td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">taxonomy working group, 109</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">taxonomy-defined dimension, 19, 22, 26–29, 40, 42, 43, 46, 47–48, 53, 72</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">deciding between explicit and typed, 74</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 96</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">explicit, 48, 74, 96</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">extension dimension, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">hypercube, 53</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">typed, 48, 75, 96</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">terse label, 84</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">transformation</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">Inline XBRL, 30</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">transport data model, 13, 30, 60, 67–77</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 95, 100</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">transport format</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 97, 102</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">selection, 77</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">typed XBRL dimension, 48, 75, 96</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">U</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">uniqueness. <i>See</i> data point uniqueness</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">unit core dimension, 19, 21, 47</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 97, 101</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">usable property, 55</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">use case, 31, 59, 60, 61, <i>92</i>, 103</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 104</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">V</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">validation, 58, 66, 80–81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">concept-based, 81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">data type, 81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">documenting, 97, 102</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">formulas, 54</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">regulatory requirement, 63</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">regulatory requirements, 81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">syntax, 81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">with CSV format, 81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">with JSON format, 81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">with XML format, 81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">verbose label, 84</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">W</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">workbook specification, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">workflow, 82, 108</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">worksheet specification, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">X</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">XBRL</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a transport model, 13, 14, 40–55, 60</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">dependent dimension, 43–46</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">dimension. <i>See</i> XBRL dimension</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">history, 6</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">independent dimensions, 42–43</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">Instance Schema, 25</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">overview, 12</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">taxonomy. See taxonomy</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">transport format, 14, 62</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195"><i>XBRL Overview</i>, <i>93</i></td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">XBRL dimension, 15, 16, 72–76</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">concept core, 19, 20, 47</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">core, 18, 19–22, 40</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">dependent dimensions, 43–46</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">dimension-default relationship, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">dimension-domain relationship, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">dimensionItem, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">domain-member relationship, 50</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">entity core, 19, 21</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">explicit, 48</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">independent dimensions, 42–43</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">language core, 19, 22, 47</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">note core ID, 29, 79</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">period core, 19, 21</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">taxonomy-defined, 22, 47–48</td>
<td class="tdh_199"></td>
</tr>
</tbody>
</table>
<p><!-- Field: Page; Sequence: 184 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->169<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

<table class="tdh_238" cellspacing="0" cellpadding="0">
<tbody>
<tr class="tdh_197">
<td class="tdh_266">unit core, 19, 21, 47</td>
<td class="tdh_236"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">XBRL Instance Schema, 25</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194"><i>XBRL Overview</i>, <i>93</i>, <i>94</i>, 99, 104</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">XBRL report, 13, 35, 71</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">comparability, 78</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">preparation, 97, 102</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">validation, 80–81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">XBRL US, 4</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL US API, 4, 11</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL US Data Quality Committee, 66</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL US Style Guide, 11</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL US Taxonomy Approval Metrics, 11</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">xLink, 49</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">XML, 6, 69</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">as a data format, 14, 27, 78</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">attribute, 7, 25</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">context, 27</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">element, 25, 83, 85</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">linkbase, 33–35, 76</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">namespace, 25, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">schema, 25, 33</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">segment, 27, 55</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">specification, 47</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">valdiation, 81</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">XBRL fact example, 27</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_195">xLink, 49</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">XML Schema Definition, 33</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">xmlns specification, 88</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_198">
<td class="tdh_188" colspan="2">Z</td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">zero-to-many relationship, 70</td>
<td class="tdh_199"></td>
</tr>
<tr class="tdh_197">
<td class="tdh_194">zero-to-one relationship, 70</td>
<td class="tdh_199"></td>
</tr>
</tbody>
</table>
<hr class="tdh_255" align="left" size="1" />
<p><!-- Field: Page; Sequence: 185 -- --></p>  

<div class="tdh_footer">Public Comment Draft #1 (11/18/2019)<span class="tdh_footer_page"><!-- Field: Sequence; Type: Arabic; Name: PageNo -->170<!-- Field: /Sequence --></span></div>
<p><!--


<div style="page-break-before: always; margin-top: 6pt; margin-bottom: 12pt">
<TABLE CELLPADDING="0" CELLSPACING="0" STYLE="border-collapse: collapse; width: 100%; font-size: 10pt">
<TR STYLE="vertical-align: top; text-align: left">
<TD STYLE="width: 50%"><A HREF="#toc">Table of Contents</A></TD>
<TD STYLE="width: 50%; text-align: right"></TD>
</TR>
</TABLE></div>


<!-- Field: /Page --></p>  

</body>
</html>
