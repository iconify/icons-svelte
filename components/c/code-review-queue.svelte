<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fpqrktb0o"/><path class="fy-aryf1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:code-review-queue" {...props}></Icon>
<style>
:global(.fpqrktb0o) {
  d: path("M13 21.5H3V6h13v4.7");
}

:global(.fy-aryf1k) {
  d: path("M7 3h10.5A2.5 2.5 0 0 1 20 5.5V11M6.5 11h6m-6 4H10m3.5 1.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm5.75 2.5l2.25 2.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
