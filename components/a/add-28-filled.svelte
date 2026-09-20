<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="iu9eofq1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:add-28-filled" {...props}></Icon>
<style>
:global(.iu9eofq1g) {
  fill: currentColor;
  d: path("M24 13h-9V4a1 1 0 1 0-2 0v9H4a1 1 0 1 0 0 2h9v9a1 1 0 1 0 2 0v-9h9a1 1 0 1 0 0-2");
}

</style>
