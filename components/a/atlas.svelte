<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n13x6dbmu"/><path class="bt29w2b2n"/><path class="yrcp9tb9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:atlas" {...props}></Icon>
<style>
:global(.bt29w2b2n) {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h12.5M8.25 10a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m0 0h9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n13x6dbmu) {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h12.5v19H7A2.5 2.5 0 0 1 4.5 19");
}

:global(.yrcp9tb9b) {
  d: path("M10.75 10a2 4.5 0 1 0 4 0a2 4.5 0 1 0-4 0");
}

</style>
