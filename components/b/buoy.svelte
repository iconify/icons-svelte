<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mj-pc85gj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:buoy" {...props}></Icon>
<style>
:global(.mj-pc85gj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.639 38.139L24 44.5l6.361-6.361m-20.5-20.5L3.5 24l6.361 6.361m20.5-20.5L24 3.5l-6.361 6.361m20.5 20.5L44.5 24l-6.361-6.361M24 16.5l7.5 7.5l-7.5 7.501l-7.5-7.5z");
}

</style>
