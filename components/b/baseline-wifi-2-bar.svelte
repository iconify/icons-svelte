<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm9xozb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-wifi-2-bar" {...props}></Icon>
<style>
:global(.bm9xozb_u) {
  fill: currentColor;
  d: path("M12 10c3.03 0 5.78 1.23 7.76 3.22l-2.12 2.12A7.97 7.97 0 0 0 12 13c-2.2 0-4.2.9-5.64 2.35l-2.12-2.12C6.22 11.23 8.97 10 12 10m0 6c-1.38 0-2.63.56-3.53 1.46L12 21l3.53-3.54A4.98 4.98 0 0 0 12 16");
}

</style>
