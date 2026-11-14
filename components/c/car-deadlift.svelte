<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7v_pybrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:car-deadlift" {...props}></Icon>
<style>
:global(.f7v_pybrh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 14.5V11q0-1.5 1.5-1.5l1.5-3.5h3.5l1.5 3.5q1.5 0 1.5 1.5v3.5M2.5 10h2v9h-2Zm17 0h2v9h-2Zm-15 4.5h15");
}

</style>
