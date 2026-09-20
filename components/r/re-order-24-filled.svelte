<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twru09agf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:re-order-24-filled" {...props}></Icon>
<style>
:global(.twru09agf) {
  fill: currentColor;
  d: path("M3 13h18a1 1 0 0 1 .117 1.993L21 15H3a1 1 0 0 1-.117-1.993zh18zm0-4h18a1 1 0 0 1 .117 1.993L21 11H3a1 1 0 0 1-.117-1.993zh18z");
}

</style>
