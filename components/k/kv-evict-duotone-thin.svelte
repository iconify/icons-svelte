<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ozusmjceo"/><path class="wimmg3bgi"/><path class="kn2e0_xvy"/><path class="prxsb9x2h"/><path class="ixy085bpz"/><path class="ab69i60qd"/><path class="q4hnnr4zu"/><path class="ly2b2eaue"/><path class="lgk47ib7d"/><path class="gorvssbqo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:kv-evict-duotone-thin" {...props}></Icon>
<style>
:global(.ab69i60qd) {
  d: path("M5.5 4H3v16h2.5");
}

:global(.gorvssbqo) {
  d: path("M17.5 9.5 20 12l-2.5 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ixy085bpz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17.5 9.5 20 12l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kn2e0_xvy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5.5 4H3v16h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lgk47ib7d) {
  d: path("M14.5 12h3");
}

:global(.ly2b2eaue) {
  d: path("M8.5 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ozusmjceo) {
  fill: currentColor;
  d: path("M8.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.prxsb9x2h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 12h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q4hnnr4zu) {
  d: path("M8.5 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.wimmg3bgi) {
  fill: currentColor;
  d: path("M8.5 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
