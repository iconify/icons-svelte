<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xi737t7bs"/><path class="beniqqiee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:combat-providence-analysis-system" {...props}></Icon>
<style>
:global(.beniqqiee) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.125 28.625L24 14.75L33.25 24L24 33.25l4.625 4.625M24 24l-4.625 4.625");
}

:global(.xi737t7bs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24L24 42.5L42.5 24L24 5.5z");
}

</style>
