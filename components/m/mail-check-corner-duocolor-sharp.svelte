<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dax2p4b0u"/><path class="epbcczbdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-check-corner-duocolor-sharp" {...props}></Icon>
<style>
:global(.dax2p4b0u) {
  stroke-opacity: 0.4;
  d: path("m15 18l2 2l4-4");
}

:global(.epbcczbdi) {
  d: path("M11 19H3V5h18v6M3 5l6 6h6l6-6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
