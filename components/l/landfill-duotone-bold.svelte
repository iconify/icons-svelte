<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gjrqt49vu"/><path class="xa9vorq4l"/><path class="agve3ib4g"/><path class="gpip01bqy"/><path class="bod4n0b3z"/><path class="e-n_8dpfy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:landfill-duotone-bold" {...props}></Icon>
<style>
:global(.agve3ib4g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 13 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.e-n_8dpfy) {
  d: path("m9 13 2 -2");
}

:global(.gjrqt49vu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m3 15 5 -5 5 5 5 -5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gpip01bqy) {
  d: path("m3 15 5 -5 5 5 5 -5 3 3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xa9vorq4l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
