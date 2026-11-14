<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="we858dadw"/><path class="jfe07_b3o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:blood-pressure-monitor" {...props}></Icon>
<style>
:global(.jfe07_b3o) {
  d: path("M7.75 16.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM16 8c5 0 5.5 4.5 3.75 7c-1.5 2-1.25 4.75 1.75 6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.we858dadw) {
  d: path("M2.5 3.5H16v17H2.5ZM6 8h6.5M6 11.75h4.5");
}

</style>
