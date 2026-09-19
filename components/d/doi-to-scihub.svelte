<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jk61qpbiq"/><path class="p_j9a5k4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:doi-to-scihub" {...props}></Icon>
<style>
:global(.jk61qpbiq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.987 11.342V42.5h31.158");
}

:global(.p_j9a5k4n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.855 5.5h31.158v31.158H10.855zm4.869 5.842h21.42m-21.42 5.842h21.42m-21.42 5.842h21.42m-21.42 5.842h11.684");
}

</style>
