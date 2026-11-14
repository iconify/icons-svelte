<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r7_z5b_vs"/><path class="ag3e92bth"/><path class="kphmxuxop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:golf-visor" {...props}></Icon>
<style>
:global(.ag3e92bth) {
  d: path("M8 8v2.5a7 3.5 0 0 0 14 0V8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kphmxuxop) {
  d: path("M11 13.25c-3.5.5-7.25 2.25-8.25 4.25C7 19 14 18 18 13.75");
}

:global(.r7_z5b_vs) {
  d: path("M8 8a7 3.5 0 1 0 14 0A7 3.5 0 1 0 8 8");
}

</style>
