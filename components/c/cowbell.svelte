<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mqz1-qshz"/><path class="y-9p-yb6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cowbell" {...props}></Icon>
<style>
:global(.mqz1-qshz) {
  d: path("M3 3.5q9 7 18 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y-9p-yb6a) {
  d: path("M8.5 6.5L6 18.5h12l-2.5-12m-5.25 12a1.75 1.75 0 0 0 3.5 0");
}

</style>
