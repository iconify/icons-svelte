<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c2xrbabwq"/><path class="ncpvyhi-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:friendiqa" {...props}></Icon>
<style>
:global(.c2xrbabwq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4z");
}

:global(.ncpvyhi-s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.223 5.5v10.294H17.777V24h12.446v8.752H17.777V42.5");
}

</style>
