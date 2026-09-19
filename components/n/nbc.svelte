<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nmf6sun5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nbc" {...props}></Icon>
<style>
:global(.nmf6sun5p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5 10.359v27.282l15.103-4.384l6.333 8.769L43 37.64V10.36l-16.564 4.385l-6.333-8.77z");
}

</style>
