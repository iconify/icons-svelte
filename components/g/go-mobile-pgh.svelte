<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q4ehap0dx"/><path class="k00u0u5rm"/><path class="jax2sc_qy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:go-mobile-pgh" {...props}></Icon>
<style>
:global(.jax2sc_qy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.835 27.87h-.012L4.5 31.726L24 37.36l19.5-5.634l-13.323-3.856h-.012");
}

:global(.k00u0u5rm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.165 20.146L43.5 24.002L30.165 27.87L24 29.648l-6.165-1.778L4.5 24.002l13.335-3.856");
}

:global(.q4ehap0dx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.496 16.281L24 10.64L4.504 16.281L24 21.923z");
}

</style>
