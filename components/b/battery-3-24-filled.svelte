<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hewcj-cbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:battery-3-24-filled" {...props}></Icon>
<style>
:global(.hewcj-cbj) {
  fill: currentColor;
  d: path("M17 6a3 3 0 0 1 3 3v1h1a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-1v1a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3zM9 9H6.017a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1H9a1 1 0 0 0 1-1v-4a1 1 0 0 0-1-1");
}

</style>
