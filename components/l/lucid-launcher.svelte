<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zvn82kp3a"/><path class="j7pdc9iiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lucid-launcher" {...props}></Icon>
<style>
:global(.j7pdc9iiu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.04 9.823L12.521 42.5h25.058");
}

:global(.zvn82kp3a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.94 5.5L10.421 38.177h25.057");
}

</style>
