<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hb0bhyban"/><path class="zerrtzqzw"/><path class="f4j-wu4yp"/><path class="bqo9tm7yv"/><path class="j53yk1bmk"/><path class="tl7fjb60a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:clear-night-duotone-regular" {...props}></Icon>
<style>
:global(.bqo9tm7yv) {
  d: path("M13 4a8 8 0 1 0 0 16 6.5 6.5 0 0 1 0 -16");
}

:global(.f4j-wu4yp) {
  fill: currentColor;
  d: path("m19 12.5 2.5 2.5 -2.5 2.5 -2.5 -2.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hb0bhyban) {
  fill: currentColor;
  d: path("M13 4a8 8 0 1 0 0 16 6.5 6.5 0 0 1 0 -16");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.j53yk1bmk) {
  d: path("M19 4.5 21.5 7 19 9.5 16.5 7Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tl7fjb60a) {
  d: path("m19 12.5 2.5 2.5 -2.5 2.5 -2.5 -2.5Z");
}

:global(.zerrtzqzw) {
  fill: currentColor;
  d: path("M19 4.5 21.5 7 19 9.5 16.5 7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
