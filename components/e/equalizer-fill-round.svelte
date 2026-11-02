<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4ly28bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:equalizer-fill-round" {...props}></Icon>
<style>
:global(.l4ly28bhl) {
  fill: currentColor;
  d: path("M7 3v8a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m6 0v2a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m6 6a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm-5-1a1 1 0 0 1 0 2h-1v11a1 1 0 0 1-2 0V10h-1a1 1 0 0 1 0-2Zm6 4a1 1 0 0 1 0 2h-1v7a1 1 0 0 1-2 0v-7h-1a1 1 0 0 1 0-2ZM8 14a1 1 0 0 1 0 2H7v5a1 1 0 0 1-2 0v-5H4a1 1 0 0 1 0-2Z");
}

</style>
