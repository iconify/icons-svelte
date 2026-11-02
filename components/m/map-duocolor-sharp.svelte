<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cf8r2lbua"/><path class="c0_52zbav"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:map-duocolor-sharp" {...props}></Icon>
<style>
:global(.c0_52zbav) {
  d: path("m3 6l6-3l6 3l6-3v15l-6 3l-6-3l-6 3z");
}

:global(.cf8r2lbua) {
  stroke-opacity: 0.4;
  d: path("M9 3v15m6-12v15");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
