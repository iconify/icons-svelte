<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="naacyowuw"/><rect class="e7cmuabej"/><path class="z5w05xy5h"/><path class="yuld0ioye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pleo" {...props}></Icon>
<style>
:global(.e7cmuabej) {
  width: 7.042px;
  height: 10.738px;
  x: 35.458px;
  y: 31.778px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.078px;
  ry: 3.078px;
}

:global(.naacyowuw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 16.222V5.484h3.48c1.967 0 3.562 1.615 3.562 3.607c0 1.991-1.595 3.606-3.562 3.606H5.5");
}

:global(.yuld0ioye) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.967 32.51H23.33V21.77h7.637");
}

:global(.z5w05xy5h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.245 15.896c-2.122 8.203 3.68 14.2 12.619 10.523");
}

</style>
