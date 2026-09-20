<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x62qrn9ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:highlight-outline" {...props}></Icon>
<style>
:global(.x62qrn9ij) {
  fill: currentColor;
  d: path("M5.65 8L3.5 5.9l1.4-1.45L7.05 6.6zM11 5V2h2v3zm7.4 3l-1.45-1.4l2.15-2.1l1.4 1.4zM9 22v-5l-3-3V9h12v5l-3 3v5zm2-2h2v-3.825l3-3V11H8v2.175l3 3zm1-4.5");
}

</style>
