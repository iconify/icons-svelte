<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qt5xlgb9e"/><path class="fv-3rdb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:muzekart" {...props}></Icon>
<style>
:global(.fv-3rdb6a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.5 24h4v18.5h-4z");
}

:global(.qt5xlgb9e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.5 42.5v-37L25 24L8.5 5.5V24");
}

</style>
