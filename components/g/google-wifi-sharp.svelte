<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9iz1xbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:google-wifi-sharp" {...props}></Icon>
<style>
:global(.d9iz1xbai) {
  fill: currentColor;
  d: path("M3.658 10.616L4.038 5h15.924l.38 5.616zM5.692 19l-.267-.846H3.173l.418-6.52H20.41l.417 6.52h-2.252l-.267.846z");
}

</style>
