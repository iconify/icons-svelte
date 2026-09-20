<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ralq96i_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-column-four-focus-center-right-20-filled" {...props}></Icon>
<style>
:global(.ralq96i_x) {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm3-2a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h.5V4zm4 12V4H7.5v12zm3 0h1a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-1z");
}

</style>
