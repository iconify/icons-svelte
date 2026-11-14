<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxbob4bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ammo-count" {...props}></Icon>
<style>
:global(.pxbob4bok) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 21V10.5q0-5.5 2-7.5q2 2 2 7.5V21ZM10 21V10.5Q10 5 12 3q2 2 2 7.5V21Zm6.75 0V10.5q0-5.5 2-7.5q2 2 2 7.5V21Z");
}

</style>
