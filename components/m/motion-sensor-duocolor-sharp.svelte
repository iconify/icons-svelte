<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dwbim_bht"/><path class="gyeupwbzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:motion-sensor-duocolor-sharp" {...props}></Icon>
<style>
:global(.dwbim_bht) {
  stroke-opacity: 0.4;
  d: path("M18 12a10 10 0 0 1-12 0m15 4a15 15 0 0 1-18 0");
}

:global(.gyeupwbzt) {
  d: path("M17 4A5 5 0 0 1 7 4M4 4h16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
