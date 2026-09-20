<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws6j20laj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:crop-portrait-outline-sharp" {...props}></Icon>
<style>
:global(.ws6j20laj) {
  fill: currentColor;
  d: path("M5 21V3h14v18zm1-1h12V4H6zm0 0V4z");
}

</style>
