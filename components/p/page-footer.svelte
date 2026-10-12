<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zbifptbkx"/><path class="rkmngterw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:page-footer" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rkmngterw) {
  d: path("M3.75 14.25v-9.5a2 2 0 0 1 2-2h12.5a2 2 0 0 1 2 2v9.5M7.5 7h9m-9 3.5h6");
}

:global(.zbifptbkx) {
  width: 16.5px;
  height: 4.75px;
  x: 3.75px;
  y: 16.5px;
  rx: 1.75px;
}

</style>
