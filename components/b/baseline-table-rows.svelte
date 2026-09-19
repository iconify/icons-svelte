<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i43b3bb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-table-rows" {...props}></Icon>
<style>
:global(.i43b3bb4i) {
  fill: currentColor;
  d: path("M21 8H3V4h18zm0 2H3v4h18zm0 6H3v4h18z");
}

</style>
