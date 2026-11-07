<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tk5lf8bih"/><path class="epbcczbdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-minus-corner-duocolor-sharp" {...props}></Icon>
<style>
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

:global(.tk5lf8bih) {
  stroke-opacity: 0.4;
  d: path("M15 17h6");
}

</style>
