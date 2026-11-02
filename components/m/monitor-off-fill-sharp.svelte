<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xw_9kob8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-off-fill-sharp" {...props}></Icon>
<style>
:global(.xw_9kob8t) {
  fill: currentColor;
  d: path("m3.707 1.293l19 19a.999.999 0 1 1-1.414 1.414L17.586 18H4a1 1 0 0 1-1-1V4c0-.164.04-.325.117-.469l-.824-.824a.999.999 0 1 1 1.414-1.414M21 15.757L8.243 3H20a1 1 0 0 1 1 1ZM9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
