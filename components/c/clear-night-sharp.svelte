<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="e5dzy6brl"/><path class="pncdzlbgq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:clear-night-sharp" {...props}></Icon>
<style>
:global(.e5dzy6brl) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 8a4.5 4.5 0 0 0 6 6a6 6 0 1 1-6-6Z");
}

:global(.pncdzlbgq) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 4.5h.01m8.49.25h.01M20 11h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
