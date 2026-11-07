<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4edlabra"/><path class="atkmu9bjw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-clock-corner-duocolor-round" {...props}></Icon>
<style>
:global(.atkmu9bjw) {
  d: path("M9 21H8a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4M8 3v2m8-2v2M4 9h16");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y4edlabra) {
  stroke-opacity: 0.4;
  d: path("M11 17a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

</style>
