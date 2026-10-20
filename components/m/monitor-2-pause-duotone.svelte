<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jw9yoiuoo"/><path class="s9pmafbmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:monitor-2-pause-duotone" {...props}></Icon>
<style>
:global(.jw9yoiuoo) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 18L5 18C2.7908 18 1 16.2092 1 14L1 6C1 3.7908 2.7908 2 5 2L19 2C21.2092 2 23 3.7908 23 6L23 14C23 16.2092 21.2092 18 19 18L13 18L13 20L16 20C16.5523 20 17 20.4477 17 21C17 21.5523 16.5523 22 16 22L8 22C7.4477 22 7 21.5523 7 21C7 20.4477 7.4477 20 8 20L11 20L11 18Z");
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s9pmafbmk) {
  d: path("M10 7L10 13M14 7L14 13");
}

</style>
