<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p7n2qqboc"/><path class="ydygllq_h"/><path class="qm17m3bad"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-sse-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p7n2qqboc) {
  d: path("M8 6h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9l3 -3Z");
}

:global(.qm17m3bad) {
  d: path("M18.95 7.05a7 7 0 0 1 0 9.9");
}

:global(.ydygllq_h) {
  d: path("M16.83 9.17a4 4 0 0 1 0 5.66");
}

</style>
