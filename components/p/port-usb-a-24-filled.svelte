<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qeokm7bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:port-usb-a-24-filled" {...props}></Icon>
<style>
:global(.qeokm7bho) {
  fill: currentColor;
  d: path("M18 8H6a2.006 2.006 0 0 0-2 2v4a2.006 2.006 0 0 0 2 2h12a2.006 2.006 0 0 0 2-2v-4a2.006 2.006 0 0 0-2-2M6 10h12v2H6z");
}

</style>
