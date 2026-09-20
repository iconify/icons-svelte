<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="nypwwpbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:minimize-28-filled" {...props}></Icon>
<style>
:global(.nypwwpbja) {
  fill: currentColor;
  d: path("M3 14a1 1 0 0 1 1-1h20a1 1 0 1 1 0 2H4a1 1 0 0 1-1-1");
}

</style>
