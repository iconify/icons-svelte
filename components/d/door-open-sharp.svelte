<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xuwjnbqhw"/><path class="o57ttnb9p"/><path class="dph_vej6h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:door-open-sharp" {...props}></Icon>
<style>
:global(.dph_vej6h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 6.5h3");
}

:global(.o57ttnb9p) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 12.5h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.xuwjnbqhw) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 2.75h13.5v18.5H5.25z");
}

</style>
