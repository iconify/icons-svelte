<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qrdjxcbap"/><path class="zirb-hbnv"/><path class="y_b-hlbjs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lobby-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qrdjxcbap) {
  d: path("M3 6v11h18V6Z");
}

:global(.y_b-hlbjs) {
  d: path("M13 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.zirb-hbnv) {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
