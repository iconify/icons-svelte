<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho7i_3bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:power-grid-sharp" {...props}></Icon>
<style>
:global(.ho7i_3bgh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3.25v18m14-18v18M2.75 5.5h4.5m9.5 0h4.5M5 5.5q7 5.5 14 0m-14 4q7 5.5 14 0");
}

</style>
