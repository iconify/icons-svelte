<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e0c96qb6a"/><path class="vddq6r-de"/><path class="faouxb3ly"/><path class="ts3tpkwrk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-3x3-linear" {...props}></Icon>
<style>
:global(.e0c96qb6a) {
  d: path("M8.69628 2.05966L8.69629 21.9721");
}

:global(.faouxb3ly) {
  d: path("M21.9502 8.68704L2.03777 8.68704");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ts3tpkwrk) {
  d: path("M21.9805 15.3135L2.03762 15.3131");
}

:global(.vddq6r-de) {
  d: path("M15.3223 2.02857L15.3218 21.9714");
}

</style>
