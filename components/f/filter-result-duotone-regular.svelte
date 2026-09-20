<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dhloj3obu"/><path class="vrfr-0-4l"/><path class="qw7b_6b1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:filter-result-duotone-regular" {...props}></Icon>
<style>
:global(.dhloj3obu) {
  fill: currentColor;
  d: path("M3 4h18l-7 7v5h-4v-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qw7b_6b1t) {
  d: path("M8 20h8");
}

:global(.vrfr-0-4l) {
  d: path("M3 4h18l-7 7v5h-4v-5Z");
}

</style>
