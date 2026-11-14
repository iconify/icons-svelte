<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og7km5y8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:compost-add" {...props}></Icon>
<style>
:global(.og7km5y8l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8h18M4 8l1.5 11.5h6.703m6.614-7.296L19 8m-8 0V4.5M11 6Q7 6 7 2.5q4 0 4 3.5Zm0-1q4 0 4-3q-4 0-4 3Zm7 10v6m-3-3h6");
}

</style>
