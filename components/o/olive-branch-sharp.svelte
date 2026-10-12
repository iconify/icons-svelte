<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u30-56bvl"/><circle class="hot64hbwf"/><circle class="rqq77ccwj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:olive-branch-sharp" {...props}></Icon>
<style>
:global(.hot64hbwf) {
  cx: 17.5px;
  cy: 13.5px;
  r: 2.25px;
}

:global(.rqq77ccwj) {
  cx: 12px;
  cy: 18.75px;
  r: 2px;
}

:global(.u30-56bvl) {
  d: path("m3.5 20.5l15-15M14 10l2 2m-7 3l1.5 1.75M8 16q.34-4.37-4-5q-.34 4.37 4 5Zm4-4q1.13-4.19-3-5.5q-1.13 4.19 3 5.5Zm4-4q1.43-3.84-2.5-5q-1.43 3.84 2.5 5Zm2.5-2.5q2.89.64 2.25-2.25q-2.89-.64-2.25 2.25Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
