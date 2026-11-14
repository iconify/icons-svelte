<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ru5jm4d0z"/><path class="segm6mgwt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:deliverable" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ru5jm4d0z) {
  d: path("M5.5 3.5h13A2.5 2.5 0 0 1 21 6a2.5 2.5 0 0 1-2.5 2.5h-13A2.5 2.5 0 0 1 3 6a2.5 2.5 0 0 1 2.5-2.5m-1 5v10a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2v-10");
}

:global(.segm6mgwt) {
  d: path("m8.5 14l2.5 2.5l4.5-4.5");
}

</style>
