<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p-p4pbbyd"/><path class="jhhox5y9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:linkwall" {...props}></Icon>
<style>
:global(.jhhox5y9b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.972 23.565l6.309 6.309l11.748-11.748");
}

:global(.p-p4pbbyd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.47c1.69 0 15.25-7.77 15.25-16.94V12.444L24 4.53L8.75 12.444V26.53c0 9.17 13.56 16.94 15.25 16.94");
}

</style>
