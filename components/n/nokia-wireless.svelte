<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hncob1bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nokia-wireless" {...props}></Icon>
<style>
:global(.hncob1bwz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.5 11c7.18 0 13 5.82 13 13s-5.82 13-13 13zm-13 0c7.18 0 13 5.82 13 13s-5.82 13-13 13zm-13 0c7.18 0 13 5.82 13 13s-5.82 13-13 13z");
}

</style>
