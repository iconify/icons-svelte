<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c-xx_e03r"/><path class="q8pnk0bty"/><path class="uk6_eqfgt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:forex-travel-money" {...props}></Icon>
<style>
:global(.c-xx_e03r) {
  d: path("M2.5 8h19v12.5h-19Zm6 0V5A1.5 1.5 0 0 1 10 3.5h4A1.5 1.5 0 0 1 15.5 5v3m-9 0v12.5M13 8v12.5");
}

:global(.q8pnk0bty) {
  d: path("M14.25 16a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.uk6_eqfgt) {
  d: path("M16.25 14h1.25a2 2 0 0 1 0 4h-1.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
