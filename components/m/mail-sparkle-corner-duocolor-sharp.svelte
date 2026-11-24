<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="amwa-x10o"/><path class="epbcczbdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-sparkle-corner-duocolor-sharp" {...props}></Icon>
<style>
:global(.amwa-x10o) {
  stroke-opacity: 0.4;
  d: path("M18 15c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
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
