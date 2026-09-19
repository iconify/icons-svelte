<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c47g5mb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:arc-launcher" {...props}></Icon>
<style>
:global(.c47g5mb-l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 5.747L5 42.253l13.004-6.765L24 24.505l5.975 11.027L43 42.253z");
}

</style>
