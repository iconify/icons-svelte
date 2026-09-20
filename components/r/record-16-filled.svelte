<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ihblhgf4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:record-16-filled" {...props}></Icon>
<style>
:global(.ihblhgf4k) {
  fill: currentColor;
  d: path("M1 8a7 7 0 1 1 14 0A7 7 0 0 1 1 8m7 4a4 4 0 1 0 0-8a4 4 0 0 0 0 8");
}

</style>
