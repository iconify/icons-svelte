<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqg2ndtqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:network-cell-outline-sharp" {...props}></Icon>
<style>
:global(.qqg2ndtqi) {
  fill: currentColor;
  d: path("M3 21L21 3v18zm13.789-1H20V5.427l-3.212 3.212z");
}

</style>
