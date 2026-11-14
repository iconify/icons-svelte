<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kaw7ibbdn"/><path class="v7cpgqhly"/><path class="g_fvw6bgl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:colour-triadic" {...props}></Icon>
<style>
:global(.g_fvw6bgl) {
  d: path("M11.5 15.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kaw7ibbdn) {
  d: path("M7 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

:global(.v7cpgqhly) {
  d: path("M2.5 15.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

</style>
