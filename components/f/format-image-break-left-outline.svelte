<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-33jhb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-image-break-left-outline" {...props}></Icon>
<style>
:global(.v-33jhb-o) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4V7h10v10zm2-2h6V9H5zM3 5V3h18v2zm5 7");
}

</style>
