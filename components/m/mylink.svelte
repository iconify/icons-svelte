<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u-ksgwy8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mylink" {...props}></Icon>
<style>
:global(.u-ksgwy8z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.023 20.334a8.172 8.172 0 1 1 .523 8.227m-.061-.092l-5.595-9.69m-2.913 8.887a8.172 8.172 0 1 1-.523-8.227m.061.092l5.595 9.69");
}

</style>
