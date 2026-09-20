<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qecovn3xi"/><path class="ujw6lacqu"/><path class="y3a01mblb"/><path class="ly22j4qka"/><path class="ywss1s28h"/><path class="xfmqtvi8p"/><path class="kn0tcm93r"/><path class="jg5k_rbda"/><path class="dhp6n31qa"/><path class="gjb6r-bki"/><path class="x8v9hpbcn"/><path class="qe18cgb-r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:git-merge-conflict-duotone-bold" {...props}></Icon>
<style>
:global(.dhp6n31qa) {
  d: path("M6 7.5V12l4.5 4.5");
}

:global(.gjb6r-bki) {
  d: path("M18 7.5V12l-4.5 4.5");
}

:global(.jg5k_rbda) {
  d: path("M16 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.kn0tcm93r) {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ly22j4qka) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 7.5V12l-4.5 4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qe18cgb-r) {
  d: path("m14.5 16.5 -5 5");
}

:global(.qecovn3xi) {
  fill: currentColor;
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ujw6lacqu) {
  fill: currentColor;
  d: path("M16 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.x8v9hpbcn) {
  d: path("m9.5 16.5 5 5");
}

:global(.xfmqtvi8p) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14.5 16.5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y3a01mblb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 7.5V12l4.5 4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ywss1s28h) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9.5 16.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
