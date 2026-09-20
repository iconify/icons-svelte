<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="meinyobsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:chat-bubble-sharp" {...props}></Icon>
<style>
:global(.meinyobsi) {
  fill: currentColor;
  d: path("M3 20.077V3h18v14H6.077z");
}

</style>
