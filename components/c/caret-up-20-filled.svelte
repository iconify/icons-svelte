<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="amnc1e-cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:caret-up-20-filled" {...props}></Icon>
<style>
:global(.amnc1e-cu) {
  fill: currentColor;
  d: path("M5.797 13.908a1 1 0 0 1-.778-1.628l3.814-4.723a1.5 1.5 0 0 1 2.334 0l3.815 4.723a1 1 0 0 1-.778 1.628z");
}

</style>
