<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ys958k_fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:grid-kanban-20-filled" {...props}></Icon>
<style>
:global(.ys958k_fe) {
  fill: currentColor;
  d: path("M3 2a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1V3a1 1 0 0 0-1-1zm0 6a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1V9a1 1 0 0 0-1-1zm0 6a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1zm9-12a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1V3a1 1 0 0 0-1-1zm0 6a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1V9a1 1 0 0 0-1-1z");
}

</style>
