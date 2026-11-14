<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="awwb4wbtx"/><path class="igd-e6byp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cubic-meter" {...props}></Icon>
<style>
:global(.awwb4wbtx) {
  d: path("M2.5 7h11v11h-11Z");
}

:global(.igd-e6byp) {
  d: path("m2.5 7l4-4h11v11l-4 4m0-11l4-4m-15 18h11m7-18v11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
