<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffw_6bc3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:list-24-filled" {...props}></Icon>
<style>
:global(.ffw_6bc3r) {
  fill: currentColor;
  d: path("M3 17h12a1 1 0 0 1 .117 1.993L15 19H3a1 1 0 0 1-.117-1.993zh12zm0-6h18a1 1 0 0 1 .117 1.993L21 13H3a1 1 0 0 1-.117-1.993zh18zm0-6h15a1 1 0 0 1 .117 1.993L18 7H3a1 1 0 0 1-.117-1.993zh15z");
}

</style>
