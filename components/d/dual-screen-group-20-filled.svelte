<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j3c9ixwwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:dual-screen-group-20-filled" {...props}></Icon>
<style>
:global(.j3c9ixwwx) {
  fill: currentColor;
  d: path("M10.5 16H16a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-5.5zm-1-12H4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h5.5z");
}

</style>
