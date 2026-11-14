<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t06moibgk"/><path class="kdk5ssq4t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:helmet-headlamp" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kdk5ssq4t) {
  d: path("M16 10za1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 16 13a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 16 10m4.25-.5l1.5-1m-1.5 5l1.5 1");
}

:global(.t06moibgk) {
  d: path("M2.5 17.5V15a6.5 6.5 0 0 1 13 0v2.5m-13 0h16");
}

</style>
