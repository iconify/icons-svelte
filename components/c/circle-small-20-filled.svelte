<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yr1cwre4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-small-20-filled" {...props}></Icon>
<style>
:global(.yr1cwre4p) {
  fill: currentColor;
  d: path("M13 10a3 3 0 1 1-6 0a3 3 0 0 1 6 0");
}

</style>
