<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xa_506f5h"/><path class="zz_qntbxb"/><path class="jh9foyc5c"/><path class="jtti8bn6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-arrow-down-minimalistic-linear" {...props}></Icon>
<style>
:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jh9foyc5c) {
  d: path("M12 11L3 11");
}

:global(.jtti8bn6v) {
  stroke-linejoin: round;
  d: path("M20 14.5L17.5 17L15 14.5M17.5 17V9");
}

:global(.xa_506f5h) {
  d: path("M20 6L3 6");
}

:global(.zz_qntbxb) {
  d: path("M11 16L3 16");
}

</style>
