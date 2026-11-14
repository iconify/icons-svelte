<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wsw43ek4d"/><path class="tm0w35jrr"/><path class="w1w4sfboj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:electronic-bill-of-lading" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tm0w35jrr) {
  d: path("M9 6.25h4l2 2v5H9Z");
}

:global(.w1w4sfboj) {
  d: path("M13 6.25v2h2");
}

:global(.wsw43ek4d) {
  d: path("M6.125 3.5h11.75A2.625 2.625 0 0 1 20.5 6.125v7.25A2.625 2.625 0 0 1 17.875 16H6.125A2.625 2.625 0 0 1 3.5 13.375v-7.25A2.625 2.625 0 0 1 6.125 3.5M2.5 19.5h19");
}

</style>
