<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="k_si6wbum"/><path class="qr13p2bua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:braille-sign-sharp" {...props}></Icon>
<style>
:global(.k_si6wbum) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v12.5H2.75zM12 15.25v6m-3.25 0h6.5");
}

:global(.qr13p2bua) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 6.5h.01M7 9h.01M7 11.5h.01m2.99-5h.01M14 9h.01M17 6.5h.01m-.01 5h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
