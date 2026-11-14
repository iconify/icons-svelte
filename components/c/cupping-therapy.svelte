<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="frg-qb6ci"/><path class="jk_r7wb7a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cupping-therapy" {...props}></Icon>
<style>
:global(.frg-qb6ci) {
  d: path("M2.5 13.5V9.75a2.25 2.25 0 0 1 4.5 0v3.75Zm7.25-.75V9a2.25 2.25 0 0 1 4.5 0v3.75Zm7.25.75V9.75a2.25 2.25 0 0 1 4.5 0v3.75Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jk_r7wb7a) {
  d: path("M2.5 18.5q9.5-6 19 0");
}

</style>
