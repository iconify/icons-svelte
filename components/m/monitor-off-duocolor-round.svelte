<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q76_okbsb"/><path class="czt_7wbte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-off-duocolor-round" {...props}></Icon>
<style>
:global(.czt_7wbte) {
  d: path("M17.647 16.647A4 4 0 0 1 16 17H8a4 4 0 0 1-4-4V8c0-1.36.679-2.561 1.716-3.284M11 4h5a4 4 0 0 1 4 4v5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q76_okbsb) {
  stroke-opacity: 0.4;
  d: path("M9 20h6M3 2l19 19");
}

</style>
