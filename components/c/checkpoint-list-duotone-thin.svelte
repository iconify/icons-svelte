<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vpuel0dtu"/><path class="bnrf8ghpe"/><path class="xexv76brg"/><path class="r3wo9dbni"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="o40l0bbgl"/><path class="a3fwgxb1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:checkpoint-list-duotone-thin" {...props}></Icon>
<style>
:global(.a3fwgxb1c) {
  d: path("M9 11.5h6");
}

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

:global(.lulmb9b1a) {
  d: path("M4 4h16v12H4");
}

:global(.o40l0bbgl) {
  d: path("M9 8.5h6");
}

:global(.r3wo9dbni) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 11.5h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vpuel0dtu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xexv76brg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 8.5h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
