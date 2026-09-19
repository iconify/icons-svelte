<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fnpgyh0wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-swipe-left-alt" {...props}></Icon>
<style>
:global(.fnpgyh0wd) {
  fill: currentColor;
  d: path("M10.1 13a5 5 0 1 0 0-2H5.83l1.59-1.59L6 8l-4 4l4 4l1.41-1.41L5.83 13z");
}

</style>
