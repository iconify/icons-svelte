<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="irbrwkyut"/><path class="qrqgcbcrf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:income-tax" {...props}></Icon>
<style>
:global(.irbrwkyut) {
  d: path("M13.6 16H2.5V4h18v7.7");
}

:global(.qrqgcbcrf) {
  d: path("M9 10a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm9 4.5v7m-3-3l3 3l3-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
