<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ezfuhbbdz"/><path class="jo6c5qbov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:help-diamond" {...props}></Icon>
<style>
:global(.ezfuhbbdz) {
  d: path("m12 2.5l9.5 9.5l-9.5 9.5L2.5 12Z");
}

:global(.jo6c5qbov) {
  d: path("M10 9.5c0-1.1.9-1.75 2-1.75s2 .65 2 1.75c0 1.5-2 1.75-2 3.25m0 3h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
