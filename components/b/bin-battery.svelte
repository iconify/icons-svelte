<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9ew1vufz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bin-battery" {...props}></Icon>
<style>
:global(.s9ew1vufz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h13v6H5Zm15.25 2v2M4 11.25h16m-14.5 0L7 21.5h10l1.5-10.25m-6.5 3v4.25");
}

</style>
