<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zyt2czbux"/><path class="d0jfembef"/><path class="a6k62accz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:contract-expired" {...props}></Icon>
<style>
:global(.a6k62accz) {
  d: path("M18 16.5V18l1.25 1");
}

:global(.d0jfembef) {
  d: path("M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zyt2czbux) {
  d: path("M13.1 21.5H4.5v-19h15v9.6M8 7h8m-8 4h8m-8 4h3");
}

</style>
