<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ii2merbrf"/><path class="q__9tb3av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:d-keys" {...props}></Icon>
<style>
:global(.ii2merbrf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22 43.5c10.77 0 19.5-8.73 19.5-19.5S32.77 4.5 22 4.5H8.5v39z");
}

:global(.q__9tb3av) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 14H22c5.523 0 10 4.477 10 10s-4.477 10-10 10h-3v-9");
}

</style>
