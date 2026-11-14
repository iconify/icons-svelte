<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pps633ibz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:comment-expand" {...props}></Icon>
<style>
:global(.pps633ibz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 2.5L12 5.75l3.5-3.25M4 11a2.5 2.5 0 0 1 2.5-2.5h11A2.5 2.5 0 0 1 20 11v4.5a2.5 2.5 0 0 1-2.5 2.5H11l-3.5 3v-3h-1A2.5 2.5 0 0 1 4 15.5Zm4 2.25h8");
}

</style>
