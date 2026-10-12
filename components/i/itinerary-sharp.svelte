<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hadkmwhbm"/><path class="xie25eb5k"/><path class="zzr_volsu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:itinerary-sharp" {...props}></Icon>
<style>
:global(.hadkmwhbm) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.75h15.5v18.5H4.25zm4 4.5v9.5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.xie25eb5k) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.25 7.25h.01M8.25 12h.01m-.01 4.75h.01");
}

:global(.zzr_volsu) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 7.25h5m-5 4.75h5m-5 4.75h3.5");
}

</style>
