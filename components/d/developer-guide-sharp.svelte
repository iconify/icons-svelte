<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ski1y769p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:developer-guide-sharp" {...props}></Icon>
<style>
:global(.ski1y769p) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm9-16v7l2.5-1.5L17 12V5z");
}

</style>
