<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3ee18b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:page-header-outline-sharp" {...props}></Icon>
<style>
:global(.i3ee18b_q) {
  fill: currentColor;
  d: path("M3 5V3h18v2zm0 16V7h18v14zm2-2h14V9H5zm0 0V9z");
}

</style>
