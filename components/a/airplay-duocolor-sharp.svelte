<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="izbywsvho"/><path class="onrz0cnly"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:airplay-duocolor-sharp" {...props}></Icon>
<style>
:global(.izbywsvho) {
  stroke-opacity: 0.4;
  d: path("M12 20H7l5-5l5 5z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.onrz0cnly) {
  d: path("M6 15H3V4h18v11h-3");
}

</style>
