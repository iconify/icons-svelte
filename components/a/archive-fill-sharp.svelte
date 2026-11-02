<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdj4a4bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:archive-fill-sharp" {...props}></Icon>
<style>
:global(.bdj4a4bgj) {
  fill: currentColor;
  d: path("M2 8V4a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-1v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V9H3a1 1 0 0 1-1-1m4 1v10h12V9Zm8 2a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
