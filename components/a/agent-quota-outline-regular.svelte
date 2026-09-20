<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u7en4tb0h"/><path class="sj1ms3civ"/><path class="mhila7bcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-quota-outline-regular" {...props}></Icon>
<style>
:global(.mhila7bcl) {
  d: path("M20 7v10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sj1ms3civ) {
  d: path("M15.27 9.28a3 3 0 1 1 -2.54 0");
}

:global(.u7en4tb0h) {
  d: path("M6.27 9.28a3 3 0 1 1 -2.54 0");
}

</style>
