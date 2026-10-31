<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i94c9r-mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:copy-20-regular" {...props}></Icon>
<style>
:global(.i94c9r-mb) {
  fill: currentColor;
  d: path("M7 7H5a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2h1a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3h2zm8-5a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3zm-4 1a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2z");
}

</style>
