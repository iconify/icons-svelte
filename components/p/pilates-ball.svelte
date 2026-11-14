<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p1zobq2vl"/><path class="n3sfkyb3t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pilates-ball" {...props}></Icon>
<style>
:global(.n3sfkyb3t) {
  d: path("M3.5 8.5q8.5 6.5 17 0");
}

:global(.p1zobq2vl) {
  d: path("M3 11.5a9 9 0 1 0 18 0a9 9 0 1 0-18 0Zm-.5 9h19");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
