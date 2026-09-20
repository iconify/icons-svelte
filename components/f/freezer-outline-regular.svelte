<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tkn_9lu9q"/><path class="xmopbdc-t"/><path class="hldvl9bwi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:freezer-outline-regular" {...props}></Icon>
<style>
:global(.hldvl9bwi) {
  d: path("m12 5 3.5 3.5L12 12 8.5 8.5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tkn_9lu9q) {
  d: path("M5 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.xmopbdc-t) {
  d: path("M5 15h14");
}

</style>
