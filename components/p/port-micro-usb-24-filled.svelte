<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brltkubvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:port-micro-usb-24-filled" {...props}></Icon>
<style>
:global(.brltkubvg) {
  fill: currentColor;
  d: path("M19 12.83V13a2.006 2.006 0 0 1-2 2H7a2.006 2.006 0 0 1-2-2v-.17a2 2 0 0 1 .59-1.42l1.82-1.82A2 2 0 0 1 8.83 9h6.34a2 2 0 0 1 1.42.59l1.82 1.82a2 2 0 0 1 .59 1.42");
}

</style>
