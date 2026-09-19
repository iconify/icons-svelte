<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n437ccb3g"/><path class="bbkk4-b1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ambitionbox" {...props}></Icon>
<style>
:global(.bbkk4-b1g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5V24l18.618 10.752");
}

:global(.n437ccb3g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.38 13.25L24 2.5l18.62 10.75v21.5L24 45.5L5.38 34.75l.002.002L24 24V13.25L5.38 24z");
}

</style>
