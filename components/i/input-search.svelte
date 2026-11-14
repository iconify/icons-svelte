<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="em4j34a7u"/><path class="kh1exgb2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:input-search" {...props}></Icon>
<style>
:global(.em4j34a7u) {
  d: path("M2.5 6h19v12h-19Z");
}

:global(.kh1exgb2y) {
  d: path("M5.25 11.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm3.5 1.5l1 1M13 12h5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
