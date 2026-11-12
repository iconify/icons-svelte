<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s19aowben"/><path class="fub8u0bsr"/><path class="q9lv46bbv"/><path class="utbx9q75k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-up-minimalistic-line-duotone" {...props}></Icon>
<style>
:global(.fub8u0bsr) {
  d: path("M20 11L3 11");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.q9lv46bbv) {
  d: path("M11 16H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.s19aowben) {
  d: path("M20 6L3 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.utbx9q75k) {
  stroke-linejoin: round;
  d: path("M14 18L17.5 15L21 18");
}

</style>
