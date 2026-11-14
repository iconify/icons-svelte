<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2cnq8t9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:float-pontoon" {...props}></Icon>
<style>
:global(.y2cnq8t9m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4.5h14m-11 0v6m8-6v6m-13.5 0h19V15h-19Zm0 8.5q2.25-1.75 4.75 0Q9.5 20.75 12 19t4.75 0t4.75 0");
}

</style>
