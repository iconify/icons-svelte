<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j0sms7xve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fedora" {...props}></Icon>
<style>
:global(.j0sms7xve) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.955 8.21a9.25 9.25 0 0 0-15.79 6.54v18.5a9.25 9.25 0 0 1-15.792 6.54M14.914 24h18.5M6.78 37.66a9.254 9.254 0 0 1 5.358-13.236m24.027-.84a9.254 9.254 0 0 0 5.383-13.243");
}

</style>
