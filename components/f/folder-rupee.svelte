<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h0qgeuwow"/><path class="x5a3qib4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:folder-rupee" {...props}></Icon>
<style>
:global(.h0qgeuwow) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.5a3 3 0 0 1 3-3h8.718a4 4 0 0 1 2.325.745l4.914 3.51a4 4 0 0 0 2.325.745H40.5a3 3 0 0 1 3 3v20a3 3 0 0 1-3 3h-33a3 3 0 0 1-3-3z");
}

:global(.x5a3qib4a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.699 18.5h3.239c2.962 0 5.363 2.406 5.363 5.375S24.9 29.25 21.938 29.25L27.3 34.5m-5.362-16h7.363m-10.602 5.401h10.602");
}

</style>
