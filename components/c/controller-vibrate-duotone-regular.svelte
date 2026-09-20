<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fp-xawcad"/><path class="dpe90gbdv"/><path class="vkmwcl8fv"/><path class="qm75-abko"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:controller-vibrate-duotone-regular" {...props}></Icon>
<style>
:global(.dpe90gbdv) {
  d: path("M8 9h8c2 0 3 2 3 5 0 2 -1 3.5 -2.5 3.5s-2.5 -2 -4.5 -2 -3 2 -4.5 2S5 16 5 14c0 -3 1 -5 3 -5");
}

:global(.fp-xawcad) {
  fill: currentColor;
  d: path("M8 9h8c2 0 3 2 3 5 0 2 -1 3.5 -2.5 3.5s-2.5 -2 -4.5 -2 -3 2 -4.5 2S5 16 5 14c0 -3 1 -5 3 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qm75-abko) {
  d: path("M21 5v4");
}

:global(.vkmwcl8fv) {
  d: path("M3 5v4");
}

</style>
