<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lvzrrfd7e"/><path class="g0krk4t6w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cage-fighter" {...props}></Icon>
<style>
:global(.g0krk4t6w) {
  d: path("M9 8.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-3 13c0-4 2.5-6.5 6-6.5s6 2.5 6 6.5");
}

:global(.lvzrrfd7e) {
  d: path("M2.5 2.5h19v19h-19Zm4 0V12m11-9.5V12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
