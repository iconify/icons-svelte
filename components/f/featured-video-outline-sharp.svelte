<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dalmmsb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:featured-video-outline-sharp" {...props}></Icon>
<style>
:global(.dalmmsb_b) {
  fill: currentColor;
  d: path("M5 14h9V7H5zm-3 6V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
