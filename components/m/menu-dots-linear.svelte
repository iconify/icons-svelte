<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="v0dnq2b7o"/><circle class="h_tsn8bxt"/><circle class="gradl1bjs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:menu-dots-linear" {...props}></Icon>
<style>
:global(.gradl1bjs) {
  cx: 19px;
  cy: 12px;
  r: 2px;
}

:global(.h_tsn8bxt) {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v0dnq2b7o) {
  cx: 5px;
  cy: 12px;
  r: 2px;
}

</style>
