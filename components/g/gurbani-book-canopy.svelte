<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2j4ojbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gurbani-book-canopy" {...props}></Icon>
<style>
:global(.y2j4ojbcy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8.5L12 3l9.5 5.5Zm1.5 0V21M20 8.5V21m-8-8q-2.5-1.5-4.75-1v7q2.25-.5 4.75 1q2.5-1.5 4.75-1v-7q-2.25-.5-4.75 1Zm0 0v7");
}

</style>
