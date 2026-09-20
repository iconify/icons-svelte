<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mn3im8sqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-3-48-regular" {...props}></Icon>
<style>
:global(.mn3im8sqq) {
  fill: currentColor;
  d: path("M4 11.25c0-.69.56-1.25 1.25-1.25h37.5a1.25 1.25 0 1 1 0 2.5H5.25c-.69 0-1.25-.56-1.25-1.25m0 13c0-.69.56-1.25 1.25-1.25h37.5a1.25 1.25 0 1 1 0 2.5H5.25c-.69 0-1.25-.56-1.25-1.25M5.25 36a1.25 1.25 0 1 0 0 2.5h37.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
