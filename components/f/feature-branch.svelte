<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z3ymw_b7g"/><path class="fvni54b1d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:feature-branch" {...props}></Icon>
<style>
:global(.fvni54b1d) {
  d: path("M15 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z3ymw_b7g) {
  d: path("M7 6.5v11m0-2c0-3 10-1 10-4.5M5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m0 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
