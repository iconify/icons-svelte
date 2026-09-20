<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq2jeobsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:event-available-sharp" {...props}></Icon>
<style>
:global(.aq2jeobsu) {
  fill: currentColor;
  d: path("M10.95 18.35L7.4 14.8l1.45-1.45l2.1 2.1l4.2-4.2l1.45 1.45zM3 22V4h3V2h2v2h8V2h2v2h3v18zm2-2h14V10H5z");
}

</style>
