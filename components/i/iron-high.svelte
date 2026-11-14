<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="acea_dbyh"/><path class="hwjf_ub_b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:iron-high" {...props}></Icon>
<style>
:global(.acea_dbyh) {
  d: path("M3 18c.5-4 4-6.5 8.5-6.5H21V18Zm7.5-6.5l1.5-5h7.5v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hwjf_ub_b) {
  fill: currentColor;
  d: path("M10 15a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m3.75 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0m3.75 0a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0");
}

</style>
