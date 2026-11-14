<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h4s22dbpt"/><path class="ktrxrkf8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:domain" {...props}></Icon>
<style>
:global(.h4s22dbpt) {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 1 0-18 0Z");
}

:global(.ktrxrkf8m) {
  d: path("M2.5 9.25h19v5.5h-19Zm6.5 0C9 6 10.25 4.25 12 3c1.75 1.25 3 3 3 6.25m-6 5.5c0 3.25 1.25 5 3 6.25c1.75-1.25 3-3 3-6.25");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
