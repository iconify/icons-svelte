<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eqoe0pbrn"/><path class="xdkxoofmo"/><path class="kxcdqacba"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:antique-shop" {...props}></Icon>
<style>
:global(.eqoe0pbrn) {
  d: path("m3 8.5l1.5-5h15l1.5 5a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0Z");
}

:global(.kxcdqacba) {
  d: path("M8 20.5v-5h4v5m3.75-6.75h5l-1.5 1.75c2.25 1 2.5 2.75 2.25 4s-1.25 2-3.25 2s-3-.75-3.25-2s0-3 2.25-4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xdkxoofmo) {
  d: path("M5.25 10.75v9.75h7.15");
}

</style>
