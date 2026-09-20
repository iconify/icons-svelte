<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="r8lmp2u_n"/><path class="sv2pgmbzl"/><path class="i0ihtoy1c"/><path class="fp0jerb6p"/><path class="tqfrzx00u"/><path class="r67lkxbgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:frame-extract-duotone-bold" {...props}></Icon>
<style>
:global(.fp0jerb6p) {
  d: path("M10.5 6H13a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h2.5");
}

:global(.i0ihtoy1c) {
  fill: currentColor;
  d: path("M6 9v6h6V9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.r67lkxbgk) {
  d: path("M6 9v6h6V9Z");
}

:global(.r8lmp2u_n) {
  fill: currentColor;
  d: path("M10.5 6H13a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h2.5");
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

:global(.sv2pgmbzl) {
  fill: currentColor;
  d: path("m19 10 3 -3v10l-3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.tqfrzx00u) {
  d: path("m19 10 3 -3v10l-3 -3Z");
}

</style>
