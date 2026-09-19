<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o34nqtg4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:coini" {...props}></Icon>
<style>
:global(.o34nqtg4o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.49 8.73C-9.25 8.55 19.36 59.79 38.29 27M15.59 5.5l19.65 34.05M10.05 8.45L29.71 42.5");
}

</style>
