<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ieioa6bqm"/><path class="vpuel0dtu"/><path class="bnrf8ghpe"/><path class="n1-hewtyq"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="hob4evbuj"/><path class="hrabrxb6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:find-checkpoint-duotone-thin" {...props}></Icon>
<style>
:global(.bnrf8ghpe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hob4evbuj) {
  d: path("M9 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hrabrxb6m) {
  d: path("M11.5 9.5 15 13");
}

:global(.ieioa6bqm) {
  fill: currentColor;
  d: path("M9 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lulmb9b1a) {
  d: path("M4 4h16v12H4");
}

:global(.n1-hewtyq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11.5 9.5 15 13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vpuel0dtu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
