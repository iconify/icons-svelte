<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r_dhm-bwn"/><path class="wa75d3r1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:overdrop" {...props}></Icon>
<style>
:global(.r_dhm-bwn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.514 23.838a4.965 4.965 0 1 1-7.026 0");
}

:global(.wa75d3r1w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.438 15.923a16.165 16.165 0 1 1-22.876 0m.001 0L24.001 4.5L35.44 15.923m-14.953 7.915l11.338-11.322m-4.311 11.322L24 20.33");
}

</style>
