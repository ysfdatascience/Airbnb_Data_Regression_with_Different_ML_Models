# Airbnb_Data_Regression_with_Different_ML_Models


<h1>Metadata of Airbnb Data</h1>

<ol>
  <li>
    <p>
      <strong>
        <code>property_type</code>
      </strong>
    </p>
    <ul>
      <li>Description: The type of property listed.</li>
      <li>Example Values: ['Apartment', 'House', 'Condominium', 'Loft', 'Townhouse', 'Hostel', 'Guest suite', 'Bed & Breakfast', 'Bungalow', 'Guesthouse', 'Dorm', 'Other', 'Camper/RV', 'Villa', 'Boutique hotel', 'Timeshare', 'In-law', 'Boat', 'Serviced apartment', 'Castle', 'Cabin', 'Treehouse', 'Tipi', 'Vacation home', 'Tent', 'Hut', 'Casa particular', 'Chalet', 'Yurt', 'Earth House', 'Parking Space', 'Train', 'Cave', 'Lighthouse', 'Island'] </li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>room_type</code>
      </strong>
    </p>
    <ul>
      <li>Description: The type of space being offered.</li>
      <li>Example Values: <ul>
          <li>
            <em>Entire home/apt</em>: The entire property is available.
          </li>
          <li>
            <em>Private room</em>: A private room within a shared property.
          </li>
          <li>
            <em>Shared room</em>: A shared room within a property.
          </li>
        </ul>
      </li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>accommodates</code>
      </strong>
    </p>
    <ul>
      <li>Description: The total number of guests the property can accommodate.</li>
      <li>Data Type: Numeric.</li>
      <li>Example: 2, 4, 6.</li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>bathrooms</code>
      </strong>
    </p>
    <ul>
      <li>Description: The total number of bathrooms available.</li>
      <li>Data Type: Numeric.</li>
      <li>Example: 1, 2, 5</li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>bed_type</code>
      </strong>
    </p>
    <ul>
      <li>Description: The type of bed provided in the listing.</li>
      <li>Example Values: ['Real Bed', 'Futon', 'Pull-out Sofa', 'Couch', 'Airbed'] </li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>bedrooms</code>
      </strong>
    </p>
    <ul>
      <li>Description: The total number of bedrooms available in the property.</li>
      <li>Data Type: Numeric.</li>
      <li>Example: 1, 2, 3.</li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>beds</code>
      </strong>
    </p>
    <ul>
      <li>Description: The total number of beds provided in the property.</li>
      <li>Data Type: Numeric.</li>
      <li>Example: 2, 4, 5.</li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>cancellation_policy</code>
      </strong>
    </p>
    <ul>
      <li>Description: The cancellation policy set by the host.</li>
      <li>Example Values: ['strict', 'moderate', 'flexible', 'super_strict_30', 'super_strict_60']</li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>cleaning_fee</code>
      </strong>
    </p>
    <ul>
      <li>Description: The cleaning fee charged by the host (if applicable).</li>
     <li>Data Type: Boolean ( <em>True</em> or <em>False</em>). </li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>city</code>
      </strong>
    </p>
    <ul>
      <li>Description: The city where the property is located.</li>
      <li>Example: ['NYC', 'SF', 'DC', 'LA', 'Chicago', 'Boston'] </li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>host_has_profile_pic</code>
      </strong>
    </p>
    <ul>
      <li>Description: Indicates whether the host has uploaded a profile picture.</li>
      <li>Data Type: Boolean ( <em>True</em> or <em>False</em>). </li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>host_identity_verified</code>
      </strong>
    </p>
    <ul>
      <li>Description: Indicates whether the host's identity has been verified.</li>
      <li>Data Type: Boolean ( <em>True</em> or <em>False</em>). </li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>host_response_rate</code>
      </strong>
    </p>
    <ul>
      <li>Description: The percentage of messages the host responds to.</li>
      <li>Data Type: Numeric (0–100 range).</li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>instant_bookable</code>
      </strong>
    </p>
    <ul>
      <li>Description: Indicates whether the property can be booked instantly without host approval.</li>
      <li>Data Type: Boolean ( <em>True</em> or <em>False</em>). </li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>first_review</code>
      </strong>
    </p>
    <ul>
      <li>Description: The date of the first review for the property.</li>
      <li>Data Type: Date.</li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>last_review</code>
      </strong>
    </p>
    <ul>
      <li>Description: The date of the most recent review for the property.</li>
      <li>Data Type: Date.</li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>neighbourhood</code>
      </strong>
    </p>
    <ul>
      <li>Description: The neighborhood or area where the property is located.</li>
      <li>Example: <em>Brooklyn</em>, <em>Downtown</em>, <em>Montmartre</em>. </li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>number_of_reviews</code>
      </strong>
    </p>
    <ul>
      <li>Description: The total number of reviews received for the property.</li>
      <li>Data Type: Numeric.</li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>review_scores_rating</code>
      </strong>
    </p>
    <ul>
      <li>Description: The overall rating score given to the property by guests.</li>
      <li>Data Type: Numeric (0–100 range).</li>
    </ul>
  </li>
  <li>
    <p>
      <strong>
        <code>log_price</code>
      </strong>
    </p>
    <ul>
      <li>Description: The log-transformed price of the property.</li>
    </ul>
  </li>
</ol>
