<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sth84_b8f"/><path class="qmfmmibza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pos-layaway" {...props}></Icon>
<style>
:global(.qmfmmibza) {
  d: path("m3 7l9 4.5L21 7m-9 4.5v.9M7.5 4.75l9 4.5m-2 6h7v6.5h-7Zm0 2.5h7m-5-3.75v1.75m3-1.75v1.75");
}

:global(.sth84_b8f) {
  d: path("M11.664 21.332L3 17V7l9-4.5L21 7v4.238");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
