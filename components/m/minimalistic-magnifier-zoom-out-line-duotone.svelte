<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="r0xhknb7f"/><path class="cq5xp9n1p"/><path class="mj_6ev9oe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimalistic-magnifier-zoom-out-line-duotone" {...props}></Icon>
<style>
:global(.cq5xp9n1p) {
  d: path("M9 11.5H11.5H14");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mj_6ev9oe) {
  d: path("M20 20L22 22");
}

:global(.r0xhknb7f) {
  cx: 11.5px;
  cy: 11.5px;
  r: 9.5px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
