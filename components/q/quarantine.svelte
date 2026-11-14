<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dj8c07bjd"/><path class="ce7e_ofiz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:quarantine" {...props}></Icon>
<style>
:global(.ce7e_ofiz) {
  d: path("M14.25 14h7.5v3c0 2.5-1.5 4.25-3.75 5c-2.25-.75-3.75-2.5-3.75-5Z");
}

:global(.dj8c07bjd) {
  d: path("M11.723 19.5H2.5v-10l8.5-7l8.5 7v1.677");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
