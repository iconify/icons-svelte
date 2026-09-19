<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h0qgeuwow"/><path class="h2oz5hgyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:folderly" {...props}></Icon>
<style>
:global(.h0qgeuwow) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.5a3 3 0 0 1 3-3h8.718a4 4 0 0 1 2.325.745l4.914 3.51a4 4 0 0 0 2.325.745H40.5a3 3 0 0 1 3 3v20a3 3 0 0 1-3 3h-33a3 3 0 0 1-3-3z");
}

:global(.h2oz5hgyi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 16.5v-3.255a3 3 0 0 0-3-3H19.943M24 33.704c0-6.25-1.25-7.5-7.5-7.5c6.25 0 7.5-1.25 7.5-7.5c0 6.25 1.25 7.5 7.5 7.5c-6.25 0-7.5 1.25-7.5 7.5");
}

</style>
