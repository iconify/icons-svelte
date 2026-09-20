<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tgfctcl1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:poll-horizontal-20-filled" {...props}></Icon>
<style>
:global(.tgfctcl1w) {
  fill: currentColor;
  d: path("M18 10a2 2 0 0 0-2-2H4a2 2 0 1 0 0 4h12a2 2 0 0 0 2-2m-8-6a2 2 0 0 0-2-2H4a2 2 0 1 0 0 4h4a2 2 0 0 0 2-2m4 12a2 2 0 0 0-2-2H4a2 2 0 1 0 0 4h8a2 2 0 0 0 2-2");
}

</style>
