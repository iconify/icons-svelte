<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uk1w1tchk"/><path class="x4r46rbgt"/><path class="cnwtrqmag"/><path class="uly3_zloy"/><path class="tahjarbfs"/><path class="rw6ho_bav"/><path class="ftjlxk3sh"/><path class="dgur4c9cy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:motel-duotone-thin" {...props}></Icon>
<style>
:global(.cnwtrqmag) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 21v-3.5h4V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dgur4c9cy) {
  d: path("M14 21v-3.5h4V21");
}

:global(.ftjlxk3sh) {
  d: path("M4 21v-3.5h4V21");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rw6ho_bav) {
  d: path("M2 9h20");
}

:global(.tahjarbfs) {
  d: path("M2 15V5h20v10");
}

:global(.uk1w1tchk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 15V5h20v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uly3_zloy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 21v-3.5h4V21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x4r46rbgt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 9h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
