<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pglhpvv_g"/><path class="ybpe0hbrk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:category-camping" {...props}></Icon>
<style>
:global(.pglhpvv_g) {
  d: path("M2.5 20L12 4l9.5 16Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ybpe0hbrk) {
  d: path("m9.5 20l2.5-7l2.5 7");
}

</style>
