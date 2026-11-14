<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aphvy1aeu"/><path class="mgyn15bzm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:goalkeeper-dive" {...props}></Icon>
<style>
:global(.aphvy1aeu) {
  d: path("m16 8l-6 4l-4.5 3.5l-2.5 4m2.5-4l2.5 4M5.5 8A1.75 1.75 0 1 0 9 8a1.75 1.75 0 1 0-3.5 0Z");
}

:global(.mgyn15bzm) {
  d: path("M15.5 6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
