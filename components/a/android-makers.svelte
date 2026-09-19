<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x_pv8pblw"/><path class="colp78icw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:android-makers" {...props}></Icon>
<style>
:global(.colp78icw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 42.5l12.333-9.25L24 42.5l18.5-37");
}

:global(.x_pv8pblw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 24L42.5 5.5v37h-37v-37z");
}

</style>
