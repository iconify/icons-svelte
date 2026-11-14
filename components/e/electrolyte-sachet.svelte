<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q9_hvmfnd"/><path class="ixa5gea_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:electrolyte-sachet" {...props}></Icon>
<style>
:global(.ixa5gea_l) {
  d: path("m13.25 7.5l-4.5 5.75h3.5l-1.5 5.25l4.5-6h-3.5Z");
}

:global(.q9_hvmfnd) {
  d: path("M5 4.5L7 3l2 1.5L11 3l2 1.5L15 3l2 1.5L19 3v18.5H5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
