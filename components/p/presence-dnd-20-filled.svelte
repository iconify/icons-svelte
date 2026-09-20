<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wdg8faclo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:presence-dnd-20-filled" {...props}></Icon>
<style>
:global(.wdg8faclo) {
  fill: currentColor;
  d: path("M10 20c5.523 0 10-4.477 10-10S15.523 0 10 0S0 4.477 0 10s4.477 10 10 10M7 9h6a1 1 0 1 1 0 2H7a1 1 0 1 1 0-2");
}

</style>
