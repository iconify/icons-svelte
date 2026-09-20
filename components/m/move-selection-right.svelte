<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghd_aynli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:move-selection-right" {...props}></Icon>
<style>
:global(.ghd_aynli) {
  fill: currentColor;
  d: path("M10 18V6h12v12zm-4 0v-2h2v2zM6 8V6h2v2zM2 18v-2h2v2zm0-5v-2h2v2zm0-5V6h2v2z");
}

</style>
