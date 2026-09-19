<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s799_-ilf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:atomic" {...props}></Icon>
<style>
:global(.s799_-ilf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.06 5.96L12.7 42.04M35.61 5.96l-6.36 36.08M7.41 15.71H43.5m-39 16.5h36.09");
}

</style>
