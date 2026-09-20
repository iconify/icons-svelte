<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mb5-b37eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:chrome-reader-mode-outline-sharp" {...props}></Icon>
<style>
:global(.mb5-b37eb) {
  fill: currentColor;
  d: path("M3 19V5h18v14zm1-1h7.5V6H4zm8.5 0H20V6h-7.5zm1.077-8.308h5.346v-.884h-5.346zm0 2.5h5.346v-.884h-5.346zm0 2.5h5.346v-.884h-5.346zM4 6v12z");
}

</style>
