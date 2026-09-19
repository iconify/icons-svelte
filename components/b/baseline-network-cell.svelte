<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb235eb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-network-cell" {...props}></Icon>
<style>
:global(.gb235eb5s) {
  fill: currentColor;
  d: path("M2 22h20V2zm18-2h-3V9.83l3-3z");
}

</style>
