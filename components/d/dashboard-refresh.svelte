<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i9aae7ayw"/><path class="ia167rb4j"/><path class="aispypb3t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dashboard-refresh" {...props}></Icon>
<style>
:global(.aispypb3t) {
  d: path("m16.5 13.5l1.5 1.25L16.5 16");
}

:global(.i9aae7ayw) {
  d: path("M13.1 21.5H2.5v-19h19V14m-19-3H15m2.8 0h3.7M11 11v10.5");
}

:global(.ia167rb4j) {
  d: path("m6 8l3-2.25l3.5 1.5L18 5.5M21.25 18A3.25 3.25 0 1 1 18 14.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
