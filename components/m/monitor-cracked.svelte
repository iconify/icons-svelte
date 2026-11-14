<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iau37ab1m"/><path class="z4vx53glw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:monitor-cracked" {...props}></Icon>
<style>
:global(.iau37ab1m) {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-4 0h8");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z4vx53glw) {
  d: path("m14.5 3.5l-2.5 4l2 2l-2.5 3l1 4");
}

</style>
