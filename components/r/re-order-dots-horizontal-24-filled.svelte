<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mh8-grb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:re-order-dots-horizontal-24-filled" {...props}></Icon>
<style>
:global(.mh8-grb_d) {
  fill: currentColor;
  d: path("M7 16a2 2 0 1 1-4 0a2 2 0 0 1 4 0m0-8a2 2 0 1 1-4 0a2 2 0 0 1 4 0m7 8a2 2 0 1 1-4 0a2 2 0 0 1 4 0m0-8a2 2 0 1 1-4 0a2 2 0 0 1 4 0m7 8a2 2 0 1 1-4 0a2 2 0 0 1 4 0m0-8a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

</style>
