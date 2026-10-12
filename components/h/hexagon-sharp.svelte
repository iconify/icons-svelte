<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hazq3_bed"/><path class="to8m3ibcr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hexagon-sharp" {...props}></Icon>
<style>
:global(.hazq3_bed) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.5 13.73l-2.75 4.77l-1 1.73h-9.5l-1-1.73l-2.75-4.77l-1-1.73l1-1.73L6.25 5.5l1-1.73h9.5l1 1.73l2.75 4.77l1 1.73z");
}

:global(.to8m3ibcr) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
