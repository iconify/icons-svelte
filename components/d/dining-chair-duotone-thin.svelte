<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y185wqbff"/><path class="h8f-l8mxz"/><path class="yyycpdbdg"/><path class="jakiyuxzs"/><path class="rrxc-4bqr"/><path class="ckxsheb0b"/><path class="z22xlf92i"/><path class="u3jess8hd"/><path class="o682nlgep"/><path class="r182r524c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dining-chair-duotone-thin" {...props}></Icon>
<style>
:global(.ckxsheb0b) {
  d: path("M7 3v10h10V3");
}

:global(.h8f-l8mxz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 16h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jakiyuxzs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 16v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o682nlgep) {
  d: path("M17 16v5");
}

:global(.r182r524c) {
  d: path("M7 9h10");
}

:global(.rrxc-4bqr) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 9h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.u3jess8hd) {
  d: path("M7 16v5");
}

:global(.y185wqbff) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3v10h10V3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yyycpdbdg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 16v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z22xlf92i) {
  d: path("M5 16h14");
}

</style>
