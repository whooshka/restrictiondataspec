# Restriction data specification- License
An open standard under CC-BY-SA v.4 for the consistent digital representation of street parking signage restriction data from **anywhere** in the world.
Please refer to the License.txt file for the full terms of the license, or creativecommons.org.

# What it is
This is a json based specification that expresses street-parking restrictions (as found on street parking signs) in a consistent format.  

#What is in the Repo
The repo has two representations of the spec, being developed in parallel. One represents parking "profiles" (see below for meaning of "profile") as objects within an object. The second represents parking "profiles" as objects in an array. In both cases each "profile" that applies to the parking bay/area is a represented as a single object.  Since the typical parking bay has multiple profiles, the collection of profiles are presented within an object or array, hence the two files in paralle.  Ideally, we settle on the one spec. 

# Why it matters
Whooshka is making this standard openly available to encourage hackers and civic minded people around the world to build tools that digitises street parking data, as LGAs and Councils often don't have the resources to do it, or maintain it once done.

# What is a restriction "profile"
In congested areas, street parking signages are often a nightmare because they have multiple "profiles".  A profile is basically a restriction that applies at that place, at that precise day, date, and time, and for individuals allowed to park there. A profile could also include prohibitions from parking, standing cars, loading-only zones, etc. The reason this gets very confusing is multiple profiles may crowd a single sign, making it all but incomprehensible.  By standardising the way we digitally store, parse and express this data, we can build tools and functionalities that help local governments manage and plan parking restrictions and also help digital applicatons display only contextually relevant signage data.  This is what Whooshka.me does.

Take a look at whooshka.me and if our mission appeals to you, we'd love to hear from you!



# Data Types
All values are expressed as strings, unless they're booleans.  This is done to ensure that type casting is done at the time of implementation and to reduce complexity in the standard.

Dates are therefore expressed according to [ISO 8601 standards](https://www.iso.org/iso-8601-date-and-time-format.html "ISO8601")





