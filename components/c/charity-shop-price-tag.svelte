<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uzrs19_wt"/><path class="why8lngmx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:charity-shop-price-tag" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uzrs19_wt) {
  d: path("M2.75 2.75H10L17.25 10L10 17.25L2.75 10Z");
}

:global(.why8lngmx) {
  d: path("M5.5 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm13 14.5l-2.75-3A2 2 0 0 1 18.5 16a2 2 0 0 1 2.75 2.5Z");
}

</style>
