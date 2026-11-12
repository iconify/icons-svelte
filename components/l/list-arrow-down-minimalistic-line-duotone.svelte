<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s19aowben"/><path class="gu4phnm0x"/><path class="kfn-_lbds"/><path class="jtti8bn6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-arrow-down-minimalistic-line-duotone" {...props}></Icon>
<style>
:global(.gu4phnm0x) {
  d: path("M11 16L3 16");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jtti8bn6v) {
  stroke-linejoin: round;
  d: path("M20 14.5L17.5 17L15 14.5M17.5 17V9");
}

:global(.kfn-_lbds) {
  d: path("M12 11L3 11");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.s19aowben) {
  d: path("M20 6L3 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
