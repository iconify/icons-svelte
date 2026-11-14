<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dplbpebxb"/><path class="fb9yq9_-h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:cloning" {...props}></Icon>
<style>
:global(.dplbpebxb) {
  d: path("M2.5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

:global(.fb9yq9_-h) {
  fill: currentColor;
  d: path("M10 15.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
