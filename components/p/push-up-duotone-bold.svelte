<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="umge8xb0s"/><path class="z5f7ktuvf"/><path class="p949upesk"/><path class="uj1zt6bpk"/><path class="xa9vorq4l"/><path class="a3zqh3bcj"/><path class="hpmnlabtt"/><path class="yg08zkbcc"/><path class="zmo9x5bsa"/><path class="bod4n0b3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:push-up-duotone-bold" {...props}></Icon>
<style>
:global(.a3zqh3bcj) {
  d: path("M2 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.bod4n0b3z) {
  d: path("M2 18h20");
}

:global(.hpmnlabtt) {
  d: path("M6 9h12");
}

:global(.p949upesk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uj1zt6bpk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 9v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.umge8xb0s) {
  fill: currentColor;
  d: path("M2 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.xa9vorq4l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yg08zkbcc) {
  d: path("M8 9v7");
}

:global(.z5f7ktuvf) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 9h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zmo9x5bsa) {
  d: path("M18 9v7");
}

</style>
