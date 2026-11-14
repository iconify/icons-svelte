<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="it6g62bic"/><path class="qgvnjzqkq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fluid-flow" {...props}></Icon>
<style>
:global(.it6g62bic) {
  d: path("M3 11.5c3 0 3-4 6-4s3 4 6 4s3-4 6-4m-18 11c3 0 3-4 6-4s3 4 6 4s3-4 6-4");
}

:global(.qgvnjzqkq) {
  d: path("M18.5 5L21 7.5L18.5 10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
