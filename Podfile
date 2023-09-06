# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

flutter_application_path = '../swift_todo_app_module'
load File.join(flutter_application_path, '.ios', 'Flutter', 'podhelper.rb')


target 'TodoApp' do
  # Comment the next line if you don't want to use dynamic frameworks
  
  use_frameworks!
  install_all_flutter_pods(flutter_application_path)

  post_install do |installer|
    flutter_post_install(installer) if defined?(flutter_post_install)
  end

  
  # Pods for TodoApp

  target 'TodoAppTests' do
    inherit! :search_paths
    # Pods for testing
  end

  target 'TodoAppUITests' do
    # Pods for testing
  end

end
