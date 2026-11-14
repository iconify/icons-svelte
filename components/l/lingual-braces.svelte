<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qm8smsbpr"/><path class="liu14zbck"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lingual-braces" {...props}></Icon>
<style>
:global(.liu14zbck) {
  d: path("M4.75 10h2.5v2.5h-2.5Zm6 0h2.5v2.5h-2.5Zm6 0h2.5v2.5h-2.5Z");
}

:global(.qm8smsbpr) {
  d: path("M3 6.5q9-3 18 0V15a3 3 0 0 1-6 0a3 3 0 0 1-6 0a3 3 0 0 1-6 0Zm4.25 4.75h9.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
