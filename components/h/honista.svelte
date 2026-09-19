<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fe784cdxa"/><path class="cf_ovwbpb"/><circle class="nr4-5w6kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:honista" {...props}></Icon>
<style>
:global(.cf_ovwbpb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.9 26.87h-7.8l-3.9 6.755l3.9 6.755h7.8l3.9-6.755zm11.7-6.755h-7.8l-3.9 6.755l3.9 6.755h7.8l3.9-6.755zM27.9 13.36h-7.8l-3.9 6.755l3.9 6.755h7.8l3.9-6.755zm-7.8 0l-1.95-3.377h-2.212M27.9 13.36l1.95-3.377h2.212");
}

:global(.fe784cdxa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.2 20.115H8.4L4.5 26.87l3.9 6.755h7.8l3.9-6.755z");
}

:global(.nr4-5w6kw) {
  cx: 39.06px;
  cy: 9.983px;
  r: 2.363px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
