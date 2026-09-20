<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r4yb1wblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-left-16-filled" {...props}></Icon>
<style>
:global(.r4yb1wblp) {
  fill: currentColor;
  d: path("M14 8a.75.75 0 0 1-.75.75H4.463l3.287 2.941a.75.75 0 1 1-1 1.118L2 8.559A.75.75 0 0 1 2 7.44l4.75-4.25a.75.75 0 1 1 1 1.118L4.463 7.25h8.787A.75.75 0 0 1 14 8");
}

</style>
