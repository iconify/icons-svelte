<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iw4w3db_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:book-clock-20-filled" {...props}></Icon>
<style>
:global(.iw4w3db_h) {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v11a1 1 0 0 1-1 1H5a1 1 0 0 0 1 1h9.5a.5.5 0 0 1 0 1H6a2 2 0 0 1-2-2zm6 9a4 4 0 1 0 0-8a4 4 0 0 0 0 8m-.5-6a.5.5 0 0 1 .5.5V9h1a.5.5 0 0 1 0 1H9.5a.5.5 0 0 1-.5-.5v-2a.5.5 0 0 1 .5-.5");
}

</style>
