<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u38qczjqj"/><path class="pwifkhr-v"/><path class="lw7cnobek"/><path class="xwbym4b8b"/><path class="srjp1meri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:headset-outline-regular" {...props}></Icon>
<style>
:global(.lw7cnobek) {
  d: path("M17 13a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pwifkhr-v) {
  d: path("M3 13a2 2 0 0 1 2 -2 2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2Z");
}

:global(.srjp1meri) {
  d: path("M11.5 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.u38qczjqj) {
  d: path("M4 11a8 8 0 0 1 16 0");
}

:global(.xwbym4b8b) {
  d: path("M21 18v3h-6");
}

</style>
