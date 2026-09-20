<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pdtixycdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:align-space-evenly-horizontal-20-filled" {...props}></Icon>
<style>
:global(.pdtixycdk) {
  fill: currentColor;
  d: path("M4 16a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2H3a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2zm6 0a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2H9a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2zm6 0a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-1a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2z");
}

</style>
