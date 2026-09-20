<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcry-ob_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:bottom-sheets-outline-sharp" {...props}></Icon>
<style>
:global(.wcry-ob_o) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-9h14V5H5zm0 2v5h14v-5zm0 0v5z");
}

</style>
