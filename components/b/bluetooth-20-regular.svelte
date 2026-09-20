<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vza6-73lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:bluetooth-20-regular" {...props}></Icon>
<style>
:global(.vza6-73lz) {
  fill: currentColor;
  d: path("M9.309 2.038a.5.5 0 0 1 .545.108l4 4a.5.5 0 0 1-.025.73L10.26 10l3.57 3.124a.5.5 0 0 1 .025.73l-4 4A.5.5 0 0 1 9 17.5v-6.398l-3.17 2.774a.5.5 0 0 1-.66-.752L8.74 10L5.17 6.876a.5.5 0 0 1 .66-.752L9 8.898V2.5a.5.5 0 0 1 .309-.462M10 11.102v5.19l2.768-2.768zm0-2.204l2.768-2.422L10 3.707z");
}

</style>
