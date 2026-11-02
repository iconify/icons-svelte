<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dqjr7ua5o"/><path class="lg-qqfb-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:palette-duocolor-sharp" {...props}></Icon>
<style>
:global(.dqjr7ua5o) {
  stroke-opacity: 0.4;
  d: path("M7 12h.01M9 8h.01M14 7h.01M17 11h.01");
}

:global(.lg-qqfb-f) {
  d: path("M12 21a9 9 0 1 1 9-9a4 4 0 0 1-4 4h-2a2 2 0 0 0-2 2v2a1 1 0 0 1-1 1");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
