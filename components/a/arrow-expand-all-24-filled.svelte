<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur5h0ccoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-expand-all-24-filled" {...props}></Icon>
<style>
:global(.ur5h0ccoi) {
  fill: currentColor;
  d: path("M2 5a1 1 0 0 1 1-1h18a1 1 0 1 1 0 2H3a1 1 0 0 1-1-1m10 4a1 1 0 0 1 1-1h8a1 1 0 1 1 0 2h-8a1 1 0 0 1-1-1M7.707 19.707a1 1 0 0 1-1.414 0l-3-3a1 1 0 1 1 1.414-1.414L6 16.586V9a1 1 0 1 1 2 0v7.586l1.293-1.293a1 1 0 0 1 1.414 1.414z");
}

</style>
