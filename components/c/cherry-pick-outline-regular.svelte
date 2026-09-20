<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z43nfgbva"/><path class="e030h51ix"/><path class="pn-mm5bcv"/><path class="ymw3aibdo"/><path class="tla8vyn6c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cherry-pick-outline-regular" {...props}></Icon>
<style>
:global(.e030h51ix) {
  d: path("M10 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pn-mm5bcv) {
  d: path("M17 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.tla8vyn6c) {
  d: path("M12 7v8");
}

:global(.ymw3aibdo) {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.z43nfgbva) {
  d: path("M3 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
