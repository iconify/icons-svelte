<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwuydcbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:flask-volumetric" {...props}></Icon>
<style>
:global(.cwuydcbju) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 2.5v8.25a5.5 5.5 0 1 0 3 0V2.5M9 6.5h6");
}

</style>
