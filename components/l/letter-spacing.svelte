<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyss_4b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:letter-spacing" {...props}></Icon>
<style>
:global(.wyss_4b5j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 14.5l5.5-11l5.5 11m-8.75-4h6.5M3.5 19h17m-15-2l-2 2l2 2m13-4l2 2l-2 2");
}

</style>
