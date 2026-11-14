<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qm8smsbpr"/><path class="ayofe3b-z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lingual-braces" {...props}></Icon>
<style>
:global(.ayofe3b-z) {
  d: path("M6 10za1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 6 12.5a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 6 10m6 0za1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 12 12.5a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 12 10m6 0za1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 18 12.5a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 18 10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qm8smsbpr) {
  d: path("M3 6.5q9-3 18 0V15a3 3 0 0 1-6 0a3 3 0 0 1-6 0a3 3 0 0 1-6 0Zm4.25 4.75h9.5");
}

</style>
