<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="p1s9t8btb"/><path class="ttfah7bxs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:muffin-sharp" {...props}></Icon>
<style>
:global(.p1s9t8btb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12a9 7.5 0 0 1 18 0v1.25H3zm3.5 1.25h11l-1 6.25l-.208 1.021l-1.042-.021h-6.5l-1.042.021L7.5 19.5Zm3.75 0l.3 7.25m3.2-7.25l-.3 7.25");
}

:global(.ttfah7bxs) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 10.25h.01m3.74-2.5h.01m3.99 1.75h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
