<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c3r0iwb1n"/><path class="n_y0e5bmg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:channel-down" {...props}></Icon>
<style>
:global(.c3r0iwb1n) {
  d: path("M2.5 7.5h19V21h-19Zm5.5-5l4 5l4-5");
}

:global(.n_y0e5bmg) {
  d: path("M8.5 12.5L12 16l3.5-3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
