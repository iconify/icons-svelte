<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yc-ow3bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:desjardins" {...props}></Icon>
<style>
:global(.yc-ow3bjj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 3.5l17.773 10.25v20.5L24 44.5L6.227 34.25v-20.5z");
}

</style>
