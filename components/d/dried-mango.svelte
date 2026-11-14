<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ctm5six4z"/><path class="y_xfh_-pz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dried-mango" {...props}></Icon>
<style>
:global(.ctm5six4z) {
  d: path("M2.5 7.25h19a9.5 9.5 0 0 1-19 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y_xfh_-pz) {
  d: path("M5.5 7.25a6.5 6.5 0 0 0 13 0");
}

</style>
