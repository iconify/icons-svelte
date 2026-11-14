<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir5xncbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pet-dryer" {...props}></Icon>
<style>
:global(.ir5xncbfz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 5h6l1.5 1.5v4L13 12H7a3.5 3.5 0 0 1 0-7Zm0 7l-1 7.5h3.5l1-7.5m6.75-6.5q1.75-1 3.75 0m-3.75 3q1.75-1 3.75 0m-3.75 3q1.75-1 3.75 0");
}

</style>
