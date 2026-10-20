# Technical Product Management Assessment — Reddit

**Reddit – Technology, Data & Integration Analysis**

A Technical Product Management assessment focused on understanding Reddit's product architecture, technology choices, data model, SQL problem-solving, and a proposed Reddit × DuckDuckGo search integration.

## Overview

This assessment evaluates Reddit through the lens of a Product Manager working closely with engineering teams.

The analysis focuses on how product requirements translate into technology, architecture, database, API, scalability, and integration decisions.

The assessment covers:

* Reddit product and user journey analysis
* Technology stack and architecture
* Technology trade-off evaluation
* Database schema design
* SQL query analysis
* Reddit × DuckDuckGo integration strategy
* REST API contract design
* Search request flow
* Revenue sharing and click attribution
* Product and technical recommendations

## Key Areas

### 1. Product & User Journey Analysis

Mapped Reddit's core product primitives and user journey:

**Users → Subreddits → Posts → Comments → Votes**

The analysis connects user actions with the underlying data operations and system requirements, demonstrating how product behavior translates into engineering considerations.

### 2. Technology Stack & Architecture

Analyzed how Reddit's frontend, API layer, backend services, caching, databases, and search infrastructure work together.

The assessment examines technologies including:

* React
* Python
* Go
* Redis
* PostgreSQL
* Cassandra
* Elasticsearch
* REST / GraphQL APIs

A cache-first architecture is also examined, including the interaction between Redis and persistent data stores.

### 3. Technology Trade-offs

Evaluated alternative technologies against Reddit's product requirements and data characteristics.

Key comparisons include:

* PostgreSQL vs MongoDB
* Redis vs Memcached

The evaluation considers factors such as:

* Scalability
* Consistency
* Performance
* Flexibility
* Data relationships
* Product fit
* Future growth

The assessment applies a product-oriented decision framework rather than selecting technologies based only on popularity.

### 4. Database Design

Designed a relational data model around Reddit's core entities and interactions.

The analysis considers relationships between:

* Users
* Subreddits
* Posts
* Comments
* Likes / Votes

The database design is connected back to Reddit's product workflows and analytical requirements.

### 5. SQL Problem Solving

Developed SQL solutions for product and user activity analysis, including:

* Recent posts within a subreddit
* Most-liked content
* Subreddit creation activity
* Most active users
* Posts containing external URLs

The queries demonstrate practical use of joins, aggregation, filtering, grouping, ordering, and ranking-oriented analysis.

### 6. Reddit × DuckDuckGo Search Partnership

Proposed a search integration between Reddit and DuckDuckGo to surface relevant Reddit discussions within DuckDuckGo search results.

**Value proposition:**

**For Reddit**

* Increased external traffic
* Improved content discoverability
* User acquisition

**For DuckDuckGo**

* More relevant search results
* Community-generated discussions
* Increased user engagement

**For users**

* Authentic community discussions
* Community-generated answers
* Faster content discovery

### 7. Search Integration API

Designed a REST API concept for the proposed partnership:

`GET /api/v1/search/posts`

The API design includes:

* Search query
* Result limit
* Sorting
* Optional subreddit filtering
* API-key authentication
* Partner-specific keys
* Rate limiting
* Key rotation

The response is intentionally limited to the information required by the consuming search platform.

### 8. Search Request & Attribution Flow

Mapped the end-to-end journey from:

**User Search → DuckDuckGo → Reddit API → Search Service → Data/Search Layer → Reddit Result → User Click → Referral Tracking**

The assessment also proposes referral-based attribution to measure traffic and revenue generated through the partnership.

### 9. Revenue Attribution

Defined an attribution approach using referral parameters to connect partner-generated traffic with downstream engagement and revenue.

Key metrics include:

* Referral clicks
* Click-through rate
* Session duration
* Ad revenue generated
* Reddit signup conversion

A dedicated attribution service is proposed as a single source of truth for partnership measurement.

## Product Management Perspective

The assessment demonstrates the ability to connect:

**Product Requirements → User Journeys → System Architecture → Data → APIs → Metrics → Business Outcomes**

It focuses on the intersection of product management and engineering, with emphasis on scalability, system interfaces, technical trade-offs, and measurable business value.

## Deliverable

The complete assessment is available in the accompanying presentation:

**[View Technical Product Management Assessment](Technical%20Product%20Management%20Assessment%20-%20Cover.pdf)**

## Capabilities Demonstrated

**Product & Business Analysis:** Product thinking, requirement analysis, user journey mapping, stakeholder/value analysis

**Technical Product Management:** System architecture, technology evaluation, API design, scalability thinking, engineering collaboration

**Data & Analytics:** SQL, relational data modelling, product metrics, attribution analysis

**Integration Design:** REST API contracts, authentication, rate limiting, request/response design, partner integration

## Author

**Vaibhav Yadav**

Technical Product Management Assessment
