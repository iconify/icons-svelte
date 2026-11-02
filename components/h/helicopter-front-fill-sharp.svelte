<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iir1fc3pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:helicopter-front-fill-sharp" {...props}></Icon>
<style>
:global(.iir1fc3pe) {
  fill: currentColor;
  d: path("M21 2a1 1 0 0 1 0 2h-8v2.07A7.01 7.01 0 0 1 19 13v4a1 1 0 0 1-1 1h-1v2h1a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2h1v-2H9v2h1a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2h1v-2H6a1 1 0 0 1-1-1v-4a7.006 7.006 0 0 1 6-6.93V4H3a1 1 0 0 1 0-2ZM7.101 12h9.798a4.97 4.97 0 0 0-1.215-2.381l-.004-.005a5 5 0 0 0-.226-.229l-.003-.003A5 5 0 0 0 7.101 12");
}

</style>
