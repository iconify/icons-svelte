<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xa_506f5h"/><path class="nmhvanepw"/><path class="f8edcu39k"/><path class="utbx9q75k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-up-minimalistic-linear" {...props}></Icon>
<style>
:global(.f8edcu39k) {
  d: path("M11 16H3");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nmhvanepw) {
  d: path("M20 11L3 11");
}

:global(.utbx9q75k) {
  stroke-linejoin: round;
  d: path("M14 18L17.5 15L21 18");
}

:global(.xa_506f5h) {
  d: path("M20 6L3 6");
}

</style>
