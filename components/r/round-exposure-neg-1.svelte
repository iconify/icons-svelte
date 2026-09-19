<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7atf6mtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:round-exposure-neg-1" {...props}></Icon>
<style>
:global(.a7atf6mtg) {
  fill: currentColor;
  d: path("M4 12c0 .55.45 1 1 1h6c.55 0 1-.45 1-1s-.45-1-1-1H5c-.55 0-1 .45-1 1m15 6h-2V7.38L14 8.4V6.7L18.7 5h.3z");
}

</style>
