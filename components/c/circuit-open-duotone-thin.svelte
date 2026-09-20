<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ylas06exf"/><path class="gob4qybps"/><path class="mqdq6sbba"/><path class="xudngvbpe"/><path class="eez_fubsi"/><path class="c4e1y7wvc"/><path class="h36909btm"/><path class="rzbbkyb0w"/><path class="a76nyxbck"/><path class="i7lk_63qj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:circuit-open-duotone-thin" {...props}></Icon>
<style>
:global(.a76nyxbck) {
  d: path("M18 14v5");
}

:global(.c4e1y7wvc) {
  d: path("M4 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.eez_fubsi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 12 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gob4qybps) {
  fill: currentColor;
  d: path("M16 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.h36909btm) {
  d: path("M16 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i7lk_63qj) {
  d: path("m8 12 6 -6");
}

:global(.mqdq6sbba) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 5v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rzbbkyb0w) {
  d: path("M6 5v5");
}

:global(.xudngvbpe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 14v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ylas06exf) {
  fill: currentColor;
  d: path("M4 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
