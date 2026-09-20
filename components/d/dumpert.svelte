<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fuesyfb9d"/><path class="w3gvwkbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dumpert" {...props}></Icon>
<style>
:global(.fuesyfb9d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 24c0 10.217-8.283 18.5-18.5 18.5H5.5v-37H24c10.217 0 18.5 8.283 18.5 18.5");
}

:global(.w3gvwkbbu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.45 24L15.889 13.862v20.276z");
}

</style>
