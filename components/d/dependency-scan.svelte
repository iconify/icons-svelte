<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ynda_kb6k"/><path class="iahfmubwt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dependency-scan" {...props}></Icon>
<style>
:global(.iahfmubwt) {
  d: path("M3.5 6L10 9.5L16.5 6M10 9.5v7m5 1.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm4.75 2l1.75 1.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ynda_kb6k) {
  d: path("M10 2.5L16.5 6v7L10 16.5L3.5 13V6Z");
}

</style>
