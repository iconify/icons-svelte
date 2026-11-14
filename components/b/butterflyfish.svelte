<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g3_tqjb5f"/><path class="ctd21sbka"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:butterflyfish" {...props}></Icon>
<style>
:global(.ctd21sbka) {
  d: path("M11.5 5q1.5 7 0 14m-3.25-7.5h.01");
}

:global(.g3_tqjb5f) {
  d: path("m3 12l3-2c1-6.5 10-7 11.5-.5L21 7v10l-3.5-2.5C16 21 7 20.5 6 14Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
