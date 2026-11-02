<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i7pgc_e7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:menu-double-bulk-round" {...props}></Icon>
<style>
:global(.i7pgc_e7m) {
  fill: currentColor;
  d: path("M19 8a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm0 6a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Z");
}

</style>
