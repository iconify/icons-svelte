<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g6btd475d"/><path class="bkuclybie"/><path class="rencte-ct"/><path class="ta-d8051h"/><path class="jny6hfa1k"/><path class="mn-a1zb6m"/><path class="s25-orfog"/><path class="tdux9oy4s"/><path class="xh38rmboq"/><path class="n9q35emrt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dependency-map-duotone-thin" {...props}></Icon>
<style>
:global(.bkuclybie) {
  fill: currentColor;
  d: path("M17 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.g6btd475d) {
  fill: currentColor;
  d: path("M3 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jny6hfa1k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17.5 10.5 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mn-a1zb6m) {
  d: path("M3 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.n9q35emrt) {
  d: path("m17.5 10.5 -4 4");
}

:global(.rencte-ct) {
  fill: currentColor;
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s25-orfog) {
  d: path("M17 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ta-d8051h) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6.5 10.5 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tdux9oy4s) {
  d: path("M10 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.xh38rmboq) {
  d: path("m6.5 10.5 4 4");
}

</style>
