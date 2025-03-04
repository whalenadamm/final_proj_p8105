Project Proposal
================
11/7/2020

## Trends in Adult Vaccination

#### By: Maria Guzman (mgg2153), Ronae McLin (rkm2147), and Adam Whalen (amw2275)

### Motivation

A few weeks ago, one of our team members gave themselves an equivalent
of a paper cut with a metal coffee can. Remembering an episode of Arthur
(the aardvark) from childhood, in which Arthur cut himself on a lima
bean can and required a tetanus shot, this team member decided to look
up her immunization record and found that her last Tdap immunization
occurred more than 10 years ago.

This anecdote helped us realize: what kind of vaccine schedule are
adults on, if any at all? How many individuals know that the tetanus
vaccine should be received every ten years? How can we ensure that
adults know the proper vaccination schedule in order to ensure maximum
health benefit not only for themselves, but for the sake of public
health?

Recently, there has been much attention guided towards vaccinations and
immunizations. Will there be a COVID-19 vaccine in the near future?
Should vaccinations be required for children to attend school? How
accessible are facilities that offer vaccines and what are the
demographics underlying those who are vaccinated? Before we can predict
the future of vaccinations, especially participation in receiving doses,
it is important to explore current data about available vaccines. More
than ever, we are reminded about the gravity of communicable diseases
and how they can completely influence local and international
communities. A considerable portion of immunizations is focused on
children, but what about the adult population? Adult immunization is
just as important, but consistently misses the limelight. This project
will explore data that contains information about vaccines, including an
visualization and analysis. Adults often don’t think about immunizations
past the flu shot or tetanus boosters. However, travel plans abroad, or
even moments of scrapping an elbow on rusty metal, can cause the “issue”
of vaccinations to come to mind. Immunizations are important\! Let’s
look at some data that supports its presence within society.

### Final Products

  - Project review meeting with p8105 teaching staff
  - Written report
  - Github supported webpage
  - Github repo
  - Screencast

### Data Sources

  - National Health Survey
      - Vaccines included: Hepatitis B & A, Flu, Shingles, Whopping
        Cough, HPV
      - <https://www.cdc.gov/nchs/nhis/nhis_2018_data_release.htm>
      - Collection goes back to 1963
  - Behavioral Risk Factor Surveillance System (BRFSS)
      - Vaccines included: flu, pneumococcal, tetanus, and shingles
      - <https://www.cdc.gov/brfss/annual_data/annual_data.htm>
  - DOHMH Hepatitis Map - NYC open data
      - Vaccine: Hepatitis B; Shows location of facilities throughout
        NYC, services provided, etc.
      - <https://data.cityofnewyork.us/Health/DOHMH-Health-Map-Hepatitis/nk7g-qeep>
  - New York City Locations Providing Seasonal Flu Vaccinations
      - <https://data.cityofnewyork.us/Health/New-York-City-Locations-Providing-Seasonal-Flu-Vac/w9ei-idxz>
      - Annual immunization data collection in the Americas
      - <https://www.paho.org/hq/index.php?option=com_content&view=article&id=2043:data-statistics-immunization&Itemid=2032&lang=en>
  - Scraping
      - Can try to find data on vaccine opinions on the internet, could
        be cool to visualize

### Planned analyses

  - Map of locations that provide vaccinations in New York City
  - Counts of locations providing flu vaccinations by borough and
    zipcode
  - From the NHIS vaccine dataset
      - FNMEDYN: family member needing medical care but did not get
  - From BRFSS
      - <https://www.cdc.gov/brfss/annual_data/2018/pdf/codebook18_llcp-v2-508.pdf>
      - Starting around page 110, questions about vaccinations
      - Look at the counts of adults reporting vaccinations
      - Create visualization based on vaccine types: which ones are
        people reporting getting most frequently?
      - Less frequently?
      - Where do they go to get these vaccines? Doctors office?
        Pharmacy?
  - Visualization: vaccine coverage
      - <https://ais.paho.org/imm/IM_ADM2_COVERAGE-MAPS%20NorteAmerica.asp>
      - Mapping similar to the mapping shown at the above link
  - Associations between vaccinations and
      - Insurance status
      - SES
      - Gender
      - Race/ethnicity

### Timeline

  - Week 1: Find data, then import and tidying
  - Week 2: EDA and visualization of data
  - Week 3: Analysis and webpage design
  - Week 4: Complete webpage and screencast

### Coding Challenges

  - Finding enough data to complete the project
  - R being an asshole
  - Dealing with strings/factors
  - Potentially dealing with large data that might be unruly
  - How to treat missing data
  - How to standardize data across various sources
