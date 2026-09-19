<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2ee9ac9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-signal-wifi-4-bar" {...props}></Icon>
<style>
:global(.p2ee9ac9d) {
  fill: currentColor;
  d: path("M23.64 7c-.45-.34-4.93-4-11.64-4C5.28 3 .81 6.66.36 7l10.08 12.56c.8 1 2.32 1 3.12 0z");
}

</style>
