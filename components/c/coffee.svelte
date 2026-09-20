<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o148k2b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:coffee" {...props}></Icon>
<style>
:global(.o148k2b1f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 6.6h29.09v22.09a7 7 0 0 1-7 7H12.5a7 7 0 0 1-7-7zm29.09 0h5.91a2 2 0 0 1 2 2v5.7a2 2 0 0 1-2 2h-5.91zM5.5 41.4h29.09");
}

</style>
