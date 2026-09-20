<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g8_0webln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:checkmark-circle-32-regular" {...props}></Icon>
<style>
:global(.g8_0webln) {
  fill: currentColor;
  d: path("M22.707 12.707a1 1 0 0 0-1.414-1.414L14.5 18.086l-3.293-3.293a1 1 0 0 0-1.414 1.414l4 4a1 1 0 0 0 1.414 0zM16 2C8.268 2 2 8.268 2 16s6.268 14 14 14s14-6.268 14-14S23.732 2 16 2M4 16C4 9.373 9.373 4 16 4s12 5.373 12 12s-5.373 12-12 12S4 22.627 4 16");
}

</style>
