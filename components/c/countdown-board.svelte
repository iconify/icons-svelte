<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fnj-_nbmg"/><path class="xemv4mmib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:countdown-board" {...props}></Icon>
<style>
:global(.fnj-_nbmg) {
  d: path("M2.5 3.5h19v13h-19Zm4.5 13v4m10-4v4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xemv4mmib) {
  d: path("M9.5 6.75h5L12 9.5c1.75 0 2.75 1 2.75 2.25s-1 2-2.5 2c-1.25 0-2.25-.5-2.75-1.25");
}

</style>
