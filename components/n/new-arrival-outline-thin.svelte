<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tp7101bon"/><path class="yb0d-pkkp"/><path class="t0w54r8ah"/><path class="ul0m4fbfe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:new-arrival-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t0w54r8ah) {
  d: path("m9.5 14 2.5 -2.5 2.5 2.5");
}

:global(.tp7101bon) {
  d: path("M2 5h20M2 5a2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0 2.5 2.5 0 0 0 5 0");
}

:global(.ul0m4fbfe) {
  d: path("M9 17.5h6");
}

:global(.yb0d-pkkp) {
  d: path("M4 8v14h16V8");
}

</style>
