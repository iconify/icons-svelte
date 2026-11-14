<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fvqybepsk"/><path class="maeuszbrt"/><path class="awcos6mbf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:newspaper-stack" {...props}></Icon>
<style>
:global(.awcos6mbf) {
  d: path("M8.5 2.5H20A1.5 1.5 0 0 1 21.5 4v11.5m-16-3h7m-7 4h5");
}

:global(.fvqybepsk) {
  d: path("M2.5 8.5h13v13h-13Z");
}

:global(.maeuszbrt) {
  d: path("M5.5 5.5H17A1.5 1.5 0 0 1 18.5 7v11.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
