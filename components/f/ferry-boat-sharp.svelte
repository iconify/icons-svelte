<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="awvt868ui"/><path class="nlrdmwb0k"/><path class="jf39w_kts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ferry-boat-sharp" {...props}></Icon>
<style>
:global(.awvt868ui) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 5.5V2.75h3.5V5.5Zm-9.5 7v-7h14.5v7Zm0-3.5h14.5");
}

:global(.jf39w_kts) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.5h18.5l-1.75 3.9l-.439 1.097l-1.181.003H6.12l-1.181-.003L4.5 16.4Zm0 8.75c1.25 0 1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75");
}

:global(.nlrdmwb0k) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 10.85h.01m3.99 0h.01m3.99 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
