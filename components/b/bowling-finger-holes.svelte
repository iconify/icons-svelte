<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kwocv2o6o"/><path class="c85wnfbcr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bowling-finger-holes" {...props}></Icon>
<style>
:global(.c85wnfbcr) {
  d: path("M10 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm5.5-4a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm0 8.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.kwocv2o6o) {
  d: path("M3 21.5A18.5 18.5 0 0 1 21.5 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
