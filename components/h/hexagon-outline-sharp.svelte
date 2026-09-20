<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxlvejbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:hexagon-outline-sharp" {...props}></Icon>
<style>
:global(.cxlvejbkh) {
  fill: currentColor;
  d: path("M7.089 20.5L2.177 12l4.912-8.5h9.823l4.911 8.5l-4.911 8.5zm.573-1h8.677l4.313-7.5l-4.313-7.5H7.662L3.323 12zM12 12");
}

</style>
