<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a5kbrhkhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:new-20-regular" {...props}></Icon>
<style>
:global(.a5kbrhkhg) {
  fill: currentColor;
  d: path("M15.5 3a.5.5 0 0 1 .5.5v8a.5.5 0 0 1-1 0v-8a.5.5 0 0 1 .5-.5M6.146 6.146a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1-.708.708l-6-6a.5.5 0 0 1 0-.708M3.5 15a.5.5 0 0 0 0 1h8a.5.5 0 0 0 0-1z");
}

</style>
