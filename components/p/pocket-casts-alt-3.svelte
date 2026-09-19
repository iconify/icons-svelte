<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hx6wibc_i"/><path class="rui2ccxcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pocket-casts-alt-3" {...props}></Icon>
<style>
:global(.hx6wibc_i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

:global(.rui2ccxcn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 37c-7.18 0-13-5.82-13-13s5.82-13 13-13s13 5.82 13 13m.5 7.5v12m6-6h-12");
}

</style>
