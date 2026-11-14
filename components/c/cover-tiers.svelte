<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mqml52bmn"/><path class="j9szwkhlz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cover-tiers" {...props}></Icon>
<style>
:global(.j9szwkhlz) {
  d: path("M14.5 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM18 4.5v3");
}

:global(.mqml52bmn) {
  d: path("M2.5 21v-4h6.25v-3.75h5.75V9.5h7V21Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
