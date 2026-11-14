<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fu3x9xbvj"/><path class="qpay6ac8u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:revenue-stream" {...props}></Icon>
<style>
:global(.fu3x9xbvj) {
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 1 0 7 8Z");
}

:global(.qpay6ac8u) {
  d: path("M13.75 6.5c-.5-1-3.5-1-3.5.5c0 1.75 3.5.25 3.5 2c0 1.5-3 1.5-3.5.5m-7.75 9c3-3 6-3 9.5 0s6.5 3 9.5 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
