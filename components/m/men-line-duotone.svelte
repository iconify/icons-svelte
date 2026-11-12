<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="eg5cwhtid"/><path class="rbz79lbus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:men-line-duotone" {...props}></Icon>
<style>
:global(.eg5cwhtid) {
  cx: 10px;
  cy: 14px;
  r: 8px;
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rbz79lbus) {
  stroke-linejoin: round;
  d: path("M15.6359 8.33427L21.9999 2M16.9999 2H21.9999V7");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
