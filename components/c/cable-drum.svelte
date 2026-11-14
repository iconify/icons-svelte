<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ny7isebqu"/><path class="dikm_vb8y"/><path class="ox9v0_z-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cable-drum" {...props}></Icon>
<style>
:global(.dikm_vb8y) {
  d: path("M8.5 11.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

:global(.ny7isebqu) {
  d: path("M2.5 11.5a8.5 8.5 0 1 0 17 0a8.5 8.5 0 1 0-17 0ZM11 20h10.5");
}

:global(.ox9v0_z-p) {
  d: path("M11 6a5.5 5.5 0 1 1-5.5 5.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
