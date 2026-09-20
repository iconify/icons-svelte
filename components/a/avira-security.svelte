<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hsgd_gbgy"/><path class="mrip80b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:avira-security" {...props}></Icon>
<style>
:global(.hsgd_gbgy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.701 13.096c-7.595-7.595-19.91-7.595-27.505 0s-7.595 19.91 0 27.505z");
}

:global(.mrip80b8m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.949 26.848l11.066 11.066a3.799 3.799 0 1 0 5.372-5.372l-1.44-1.44");
}

</style>
