<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wq3w4bbpe"/><path class="hkubptbdt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:assessment-test" {...props}></Icon>
<style>
:global(.hkubptbdt) {
  d: path("M9 9.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3-4.5v1.5m0 3l1.25-1.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wq3w4bbpe) {
  d: path("M6.125 2.5h11.75A2.625 2.625 0 0 1 20.5 5.125v8.25A2.625 2.625 0 0 1 17.875 16H6.125A2.625 2.625 0 0 1 3.5 13.375v-8.25A2.625 2.625 0 0 1 6.125 2.5M2 19h20");
}

</style>
