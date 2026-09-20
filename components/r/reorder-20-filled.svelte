<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="th3yqyb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:reorder-20-filled" {...props}></Icon>
<style>
:global(.th3yqyb4z) {
  fill: currentColor;
  d: path("M2.75 7.75a.75.75 0 0 0 0 1.5h14.5a.75.75 0 0 0 0-1.5zm0 3a.75.75 0 0 0 0 1.5h14.5a.75.75 0 0 0 0-1.5z");
}

</style>
