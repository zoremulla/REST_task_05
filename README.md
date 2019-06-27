1. Setup a virtual environment.
2. Fork the repository for [Django REST Task 5](https://github.com/JoinCODED/REST_task_05/) in JoinCODED’s Github and Clone it.
3. Install the packages from the requirements file.
4. Modify the `BookingsList` view so that it returns the list of upcoming bookings that belong to the logged in user.
5. Modify the `UpdateBooking` view so that `admins` can modify both `passengers` and `date` while normal users can only modify `passengers`.
   * Hint: You will need to override a method. Use [this](http://www.cdrf.co/3.1/rest_framework.generics/RetrieveUpdateAPIView.html) as a reference.
6. Test both apis in postman.
7. Push your code
