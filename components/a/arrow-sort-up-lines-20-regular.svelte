<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uqyrhpbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-sort-up-lines-20-regular" {...props}></Icon>
<style>
:global(.uqyrhpbjl) {
  fill: currentColor;
  d: path("M15 17.5a.5.5 0 0 1-1 0V3.707l-2.146 2.147a.5.5 0 0 1-.708-.708l3-3a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1-.708.708L15 3.707zM2.5 16a.5.5 0 0 1 0-1h9a.5.5 0 0 1 0 1zM5 12.5a.5.5 0 0 0 .5.5h6a.5.5 0 0 0 0-1h-6a.5.5 0 0 0-.5.5M8.5 10a.5.5 0 0 1 0-1h3a.5.5 0 0 1 0 1z");
}

</style>
