<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t-euypbap"/><path class="u3t8-bfcz"/><path class="strt8mboj"/><path class="rynjb5q0q"/><path class="jnysnpbhj"/><path class="ws9v8zbhe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-dumbbell-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jnysnpbhj) {
  d: path("M17 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.rynjb5q0q) {
  d: path("M7 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.strt8mboj) {
  d: path("M7 8h6");
}

:global(.t-euypbap) {
  d: path("M3 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.u3t8-bfcz) {
  d: path("M13 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ws9v8zbhe) {
  d: path("M11 16h6");
}

</style>
