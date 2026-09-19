<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="g9mi12cgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:frosty" {...props}></Icon>
<style>
:global(.g9mi12cgg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.203 15.567c.987-.987 2.585-1.1 4.028.343L43.5 33.175h-7.7L24.048 21.41l-2.674 2.427l9.196 9.198h-7.514l-5.447-5.448l-5.459 5.46H4.5c5.766-5.835 11.93-11.655 17.705-17.48z");
}

</style>
