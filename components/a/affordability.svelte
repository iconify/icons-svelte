<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e8vdn8hxh"/><path class="g2vxby7tq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:affordability" {...props}></Icon>
<style>
:global(.e8vdn8hxh) {
  d: path("M3.5 10.5L12 3.25l8.5 7.25v10h-17ZM12 9v8");
}

:global(.g2vxby7tq) {
  d: path("m9 14l3 3l3-3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
