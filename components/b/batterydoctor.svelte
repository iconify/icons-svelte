<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yrxpivvcs"/><path class="r1gg5cv-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:batterydoctor" {...props}></Icon>
<style>
:global(.r1gg5cv-t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.868 17.5L20 26h8l-5.868 8.5");
}

:global(.yrxpivvcs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.505 4.5h6.67a1 1 0 0 1 1 1v3h4.63a2 2 0 0 1 2 2v31a2 2 0 0 1-2 2h-17.61a2 2 0 0 1-2-2v-31a2 2 0 0 1 2-2h4.31v-3a1 1 0 0 1 1-1m-1 4h8.67");
}

</style>
