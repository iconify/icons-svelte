<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="xe53owbmy"/><circle class="gm84d-bws"/><circle class="zopjch_2q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:menu-dots-vertical-line-duotone" {...props}></Icon>
<style>
:global(.gm84d-bws) {
  cx: 12px;
  cy: 12px;
  r: 2px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xe53owbmy) {
  cx: 12px;
  cy: 5px;
  r: 2px;
}

:global(.zopjch_2q) {
  cx: 12px;
  cy: 19px;
  r: 2px;
}

</style>
