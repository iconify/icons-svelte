<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t6-ei6bor"/><path class="ilsdrsbjb"/><path class="jfw7_-93z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mon-eleclerc" {...props}></Icon>
<style>
:global(.ilsdrsbjb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.023 11.774C24.73 7.8 32.578 9.207 36.55 14.915s2.566 13.555-3.142 17.528q-.17.119-.344.23");
}

:global(.jfw7_-93z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.798 14.361h8.909v2.952q-1.54.457-1.541 2.089v13.18c6.06.156 7.17-.484 7.902-2.273h1.763v5.63H13.8v-2.835c.967-.51 1.62-1.476 1.685-2.795V19.402q-.066-1.632-1.686-2.09z");
}

:global(.t6-ei6bor) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.873 0 21.5 9.627 21.5 21.5S35.873 45.5 24 45.5S2.5 35.873 2.5 24S12.127 2.5 24 2.5");
}

</style>
