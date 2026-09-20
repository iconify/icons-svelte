<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qecovn3xi"/><path class="ujw6lacqu"/><path class="n88kwi36z"/><path class="fe3w54baf"/><path class="gr3vov5wd"/><path class="kn0tcm93r"/><path class="jg5k_rbda"/><path class="qp__wx2fk"/><path class="dhp6n31qa"/><path class="gjb6r-bki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:git-merge-duotone-regular" {...props}></Icon>
<style>
:global(.dhp6n31qa) {
  d: path("M6 7.5V12l4.5 4.5");
}

:global(.fe3w54baf) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 7.5V12l4.5 4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gjb6r-bki) {
  d: path("M18 7.5V12l-4.5 4.5");
}

:global(.gr3vov5wd) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 7.5V12l-4.5 4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jg5k_rbda) {
  d: path("M16 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.kn0tcm93r) {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.n88kwi36z) {
  fill: currentColor;
  d: path("M10 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

:global(.qecovn3xi) {
  fill: currentColor;
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qp__wx2fk) {
  d: path("M10 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ujw6lacqu) {
  fill: currentColor;
  d: path("M16 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
