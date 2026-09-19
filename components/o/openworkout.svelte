<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s8wvgk0hj"/><path class="jzvgi1bpu"/><path class="o8myn5lxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:openworkout" {...props}></Icon>
<style>
:global(.jzvgi1bpu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.217 32.106L24.012 16.868l-15.234 15.2");
}

:global(.o8myn5lxo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.934 36.374l-10.92-10.945l-10.958 10.933");
}

:global(.s8wvgk0hj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.62 39.693L43.5 27.84L24.01 8.307L4.5 27.775l11.89 11.916Z");
}

</style>
