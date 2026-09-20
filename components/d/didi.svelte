<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gt2pqumwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:didi" {...props}></Icon>
<style>
:global(.gt2pqumwc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.71 10.355H4.5v7.79a19.5 19.5 0 0 0 19.5 19.5a19.5 19.5 0 0 0 19.5-19.5");
}

</style>
