<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hf7hzjbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:myfrontier" {...props}></Icon>
<style>
:global(.hf7hzjbes) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24A18.5 18.5 0 1 0 24 5.5H5.5m12.333 6.166H5.5m0 6.166h6.167");
}

</style>
