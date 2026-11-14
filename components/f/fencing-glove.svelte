<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrmiyjbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fencing-glove" {...props}></Icon>
<style>
:global(.nrmiyjbmg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.25 13V5.5a3.5 3.5 0 0 0-7 0v4L6.75 7A2 2 0 0 0 4 9.75L7.25 13m1 3h9l3 5.5h-15Zm-.5-3h10v3h-10Z");
}

</style>
