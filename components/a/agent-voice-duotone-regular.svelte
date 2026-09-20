<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gntt6lljd"/><path class="mb4qs8bov"/><path class="gplcwrbte"/><path class="dxqp15kpa"/><path class="g_ig5r7qc"/><path class="os75hg6rr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-voice-duotone-regular" {...props}></Icon>
<style>
:global(.dxqp15kpa) {
  d: path("M8.69 8.37a4 4 0 1 1 -3.38 0");
}

:global(.g_ig5r7qc) {
  d: path("M17.12 9.88a3 3 0 0 1 0 4.24");
}

:global(.gntt6lljd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.69 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gplcwrbte) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19.24 7.76a6 6 0 0 1 0 8.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mb4qs8bov) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17.12 9.88a3 3 0 0 1 0 4.24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.os75hg6rr) {
  d: path("M19.24 7.76a6 6 0 0 1 0 8.5");
}

</style>
