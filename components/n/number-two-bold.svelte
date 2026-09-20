<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="l7_1wrbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:number-two-bold" {...props}></Icon>
<style>
:global(.l7_1wrbhr) {
  fill: currentColor;
  d: path("M180 208a12 12 0 0 1-12 12H88a12 12 0 0 1-9.6-19.2l71.95-95.92a28 28 0 1 0-48-28.06a12 12 0 0 1-22-9.62a52.3 52.3 0 0 1 6.13-10.49a52 52 0 0 1 83.06 62.59L112 196h56a12 12 0 0 1 12 12");
}

</style>
