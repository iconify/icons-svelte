<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mj3a_md1p"/><path class="vjuszsbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:refra" {...props}></Icon>
<style>
:global(.mj3a_md1p) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.532 25.705L5.793 38.95L17.19 5z");
}

:global(.vjuszsbch) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.946 22.221l28.26-13.693L30.514 43zm12.25-6.037l-4.765 15.224");
}

</style>
