<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpg1m5ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-center-vertical-fill-round" {...props}></Icon>
<style>
:global(.lpg1m5ble) {
  fill: currentColor;
  d: path("M11 7v2H3V7a4 4 0 0 1 8 0m10 2h-8a4 4 0 0 1 8 0M3 11h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m0 4h8v2a4 4 0 0 1-8 0Zm10 0h8a4 4 0 0 1-8 0");
}

</style>
