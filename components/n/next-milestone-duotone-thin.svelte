<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vpuel0dtu"/><path class="bnrf8ghpe"/><path class="cqnxnfbpy"/><path class="zjhlxwb4b"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="pr2xdw8hh"/><path class="a67_cn3fi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:next-milestone-duotone-thin" {...props}></Icon>
<style>
:global(.a67_cn3fi) {
  d: path("M13.5 7.5 16 10l-2.5 2.5");
}

:global(.bnrf8ghpe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cqnxnfbpy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10.5 7.5 13 10l-2.5 2.5");
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

:global(.pr2xdw8hh) {
  d: path("M10.5 7.5 13 10l-2.5 2.5");
}

:global(.vpuel0dtu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zjhlxwb4b) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13.5 7.5 16 10l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
