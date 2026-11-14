<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kuxoreb3g"/><path class="zsl6cp7td"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ping-pong-edge-ball" {...props}></Icon>
<style>
:global(.kuxoreb3g) {
  d: path("M2.5 18L6 11h15.5L18 18Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zsl6cp7td) {
  d: path("M16 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-5.75 10l3.5-7");
}

</style>
