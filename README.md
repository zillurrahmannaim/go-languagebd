<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' b:defaultwidgetversion='2' b:layoutsVersion='3' b:responsive='true' b:templateVersion='1.0.0' expr:class='data:blog.languageDirection' expr:dir='data:blog.languageDirection' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <head>
      <meta content='width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1' name='viewport'/>
    <title><data:view.title.escaped/></title>
    <b:include data='blog' name='all-head-content'/>
<b:if cond='data:view.isHomepage'>
<script type='application/ld+json'>{&quot;@context&quot;:&quot;http://schema.org&quot;,&quot;@type&quot;:&quot;WebSite&quot;,&quot;name&quot;:&quot;<data:view.title.escaped/>&quot;,&quot;url&quot;:&quot;<data:view.url.canonical/>&quot;,&quot;potentialAction&quot;:{&quot;@type&quot;:&quot;SearchAction&quot;,&quot;target&quot;:&quot;<data:view.url.canonical/>search?q={search_term_string}&quot;,&quot;query-input&quot;:&quot;required name=search_term_string&quot;}}</script>
    </b:if>

    <!-- Google Fonts -->
    <link href='//fonts.googleapis.com/css?family=Source+Sans+Pro:400,400i,500,500i,600,600i,700,700i' media='all' rel='stylesheet' type='text/css'/>
    <link href='https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css' rel='stylesheet'/>
 
<!-- Template Style CSS -->
<b:skin version='1.0.0'><![CDATA[/*
-----------------------------------------------
Blogger Template Style
Name:        Beautly
License:     Free Version
Version:     2.0
Author:      OmTemplates
Author Url:  https://www.omtemplates.com/
----------------------------------------------- */
/*
<!-- Variable definitions -->
<Variable name="keycolor" description="Main Color" type="color" default="$(main.color)" value="#a18858"/>
<Variable name="followByEmail" description="Follow By Email Text" type="string" default="Get all latest content delivered straight to your inbox." value="Get all latest content delivered straight to your inbox."/>

<Group description="Theme Colors" selector="body">
<Variable name="main.color" description="Theme Color" type="color" default="#ff749f" value="#ffcc6a"/>
  <Variable name="main.dark.color" description="Dark Color" type="color" default="#202020" value="#333333"/>
  <Variable name="menu.color" description="Menu Color" type="color" default="#ffffff" value="#ffffff"/>
  <Variable name="title.color" description="Title Color" type="color" default="#333333" value="#000000"/>
  <Variable name="title.hover" description="Title Color on Hover" type="color" default="$(main.color)" value="#ffcc6a"/>
  <Variable name="footer.color" description="Footer Color" type="color" default="#f1ffff" value="#ececff"/>
</Group>

