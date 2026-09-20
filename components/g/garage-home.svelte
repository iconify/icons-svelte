<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl9y0kb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:garage-home" {...props}></Icon>
<style>
:global(.sl9y0kb5t) {
  fill: currentColor;
  d: path("M5 20V9.5l7-5.288L19 9.5V20h-2.5v-9.02h-9V20zm3.5-1.02h7v-3h-7zm0-4h7v-3h-7z");
}

</style>
