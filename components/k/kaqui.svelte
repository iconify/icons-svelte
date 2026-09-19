<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k26gfw30d"/><path class="mhsqwnbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kaqui" {...props}></Icon>
<style>
:global(.k26gfw30d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.4 4.5a4 4 0 0 0-4 4v31a4 4 0 0 0 4 4h23.2a4 4 0 0 0 4-4v-31a4 4 0 0 0-4-4z");
}

:global(.mhsqwnbuq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.606 8.909L16.394 24l15.212 15.091");
}

</style>
