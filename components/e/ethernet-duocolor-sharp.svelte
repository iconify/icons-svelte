<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q6v94_xbf"/><path class="gelqk848u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ethernet-duocolor-sharp" {...props}></Icon>
<style>
:global(.gelqk848u) {
  d: path("M3 4h18v13h-4v4H7v-4H3z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q6v94_xbf) {
  stroke-opacity: 0.4;
  d: path("M6 8v3m4-3v3m4-3v3m4-3v3");
}

</style>
