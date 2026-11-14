<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bx8rpubcn"/><path class="bi9vllbqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:immersive-space" {...props}></Icon>
<style>
:global(.bi9vllbqn) {
  d: path("M4.75 18a7.25 2.5 0 1 0 14.5 0a7.25 2.5 0 1 0-14.5 0Z");
}

:global(.bx8rpubcn) {
  d: path("M4.75 18a9.5 9.5 0 1 1 14.5 0");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
