<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h_die1bht"/><path class="r70nh4b3d"/><path class="n4mv5ws9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gizmo-rotate" {...props}></Icon>
<style>
:global(.h_die1bht) {
  d: path("M2.5 12a9.5 3.75 0 1 0 19 0a9.5 3.75 0 1 0-19 0Z");
}

:global(.n4mv5ws9c) {
  d: path("M10.75 12a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

:global(.r70nh4b3d) {
  d: path("M8.25 12a3.75 9.5 0 1 0 7.5 0a3.75 9.5 0 1 0-7.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
