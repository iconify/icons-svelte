<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="j5_7-jflh"/><path class="l5fw6da3f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:receipt-printer-sharp" {...props}></Icon>
<style>
:global(.j5_7-jflh) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 10.75v-7.5l1.75 1l1.75-1l1.75 1l1.75-1l1.75 1l1.75-1v7.5m-8-3.25h5.5m-12 3.25h18.5v10.5H2.75zM6.25 16h6");
}

:global(.l5fw6da3f) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 16h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
