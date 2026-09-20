<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aq1lvs8nn"/><path class="pc5t8x4uc"/><path class="wi-4s5bun"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:object-lock-outline-regular" {...props}></Icon>
<style>
:global(.aq1lvs8nn) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pc5t8x4uc) {
  d: path("M8.5 16.5a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2V19a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

:global(.wi-4s5bun) {
  d: path("M9.5 14.5a2.5 2.5 0 0 1 5 0");
}

</style>
