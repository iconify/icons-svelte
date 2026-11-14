<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zppzcnbjr"/><path class="ga8xxqb2l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:accordion" {...props}></Icon>
<style>
:global(.ga8xxqb2l) {
  d: path("m15.5 5.25l1.5 1.5l1.5-1.5m-3 9.75l1.5-1.5l1.5 1.5M5 20.25h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zppzcnbjr) {
  d: path("M5.125 3.25h13.75A2.625 2.625 0 0 1 21.5 5.875v.25a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 6.125v-.25A2.625 2.625 0 0 1 5.125 3.25m0 8.25h13.75a2.625 2.625 0 0 1 2.625 2.625v.25A2.625 2.625 0 0 1 18.875 17H5.125A2.625 2.625 0 0 1 2.5 14.375v-.25A2.625 2.625 0 0 1 5.125 11.5");
}

</style>
