<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j80l4rbyk"/><circle class="fnb_mpb7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:golf" {...props}></Icon>
<style>
:global(.fnb_mpb7x) {
  cx: 16.5px;
  cy: 17.75px;
  r: 3px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j80l4rbyk) {
  d: path("M7.25 20.75v-11m.94-6.15l7.62 2.8q.94.35 0 .7L8.19 9.9q-.94.35-.94-.65v-5q0-1 .94-.65M3.75 20.75h7");
}

</style>
