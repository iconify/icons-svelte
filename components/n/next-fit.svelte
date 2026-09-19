<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bebk-1lcv"/><path class="la_b1yb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:next-fit" {...props}></Icon>
<style>
:global(.bebk-1lcv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 4.5v39L18.833 22.833");
}

:global(.la_b1yb_k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 43.5v-39l20.667 20.667M8.5 43.5L20 32");
}

</style>
