<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="juyvbccyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:naturalreader" {...props}></Icon>
<style>
:global(.juyvbccyl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18v12m-4.5-18v12m9 0v12M6 42V6m4.5 36V6M15 42V6m18 36V6m9 36V6m-4.5 36V6");
}

</style>
