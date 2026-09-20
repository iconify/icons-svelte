<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r9vsub3-y"/><path class="niggb1byh"/><path class="gdju1xbel"/><path class="wzhctub5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:magnetic-field-duotone-regular" {...props}></Icon>
<style>
:global(.gdju1xbel) {
  d: path("M3 13c0 -9 18 -9 18 0");
}

:global(.niggb1byh) {
  d: path("M8 10h8v4H8Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r9vsub3-y) {
  fill: currentColor;
  d: path("M8 10h8v4H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wzhctub5z) {
  d: path("M3 11c0 9 18 9 18 0");
}

</style>
