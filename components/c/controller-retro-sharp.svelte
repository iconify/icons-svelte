<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="l5sfk2b5q"/><path class="rxo43kb9y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:controller-retro-sharp" {...props}></Icon>
<style>
:global(.l5sfk2b5q) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.5V2.75h2.5M2.75 7.5h18.5v10H2.75zm2.75 5H9m-1.75-1.75v3.5m3.5-.25h2.5");
}

:global(.rxo43kb9y) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 13h.01m2.99-2h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
