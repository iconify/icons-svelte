<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="unye7_bni"/><path class="o2gtpcb1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:discount-member" {...props}></Icon>
<style>
:global(.o2gtpcb1j) {
  d: path("M5.75 8.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM4.5 17a3 3 0 0 1 6 0m2-8.5H16m-3.5 4h1.8m2.2 1.75h5.25v7.5H16.5L13.75 18Zm.25 3.75h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.unye7_bni) {
  d: path("M11 17H2.5V4H19v7.4");
}

</style>
