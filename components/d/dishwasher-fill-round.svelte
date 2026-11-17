<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzfy1wg1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:dishwasher-fill-round" {...props}></Icon>
<style>
:global(.tzfy1wg1q) {
  fill: currentColor;
  d: path("M8 2h8a5 5 0 0 1 5 5v1H3V7a5 5 0 0 1 5-5m.01 3H8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M11 5a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm10 5v7a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5v-7Zm-5 2H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2");
}

</style>
