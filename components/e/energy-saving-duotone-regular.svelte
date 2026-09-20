<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bvm-k9uli"/><path class="zo_xbmb4y"/><path class="g-g566bva"/><path class="eob2zbc5p"/><path class="vqwutobjj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:energy-saving-duotone-regular" {...props}></Icon>
<style>
:global(.bvm-k9uli) {
  fill: currentColor;
  d: path("M9 13c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.eob2zbc5p) {
  d: path("M9 19h6");
}

:global(.g-g566bva) {
  d: path("M8 10v6h8v-6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vqwutobjj) {
  d: path("M9 13c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

:global(.zo_xbmb4y) {
  d: path("M6 10a6 6 0 0 1 12 0");
}

</style>
