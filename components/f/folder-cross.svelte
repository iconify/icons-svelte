<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h0qgeuwow"/><path class="ceji4ab_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:folder-cross" {...props}></Icon>
<style>
:global(.ceji4ab_x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.162 23.36v-6.071h-5.858v6.071m5.858 5.858h6.071V23.36h-6.071m-5.858 5.858v6.071h5.858v-6.071m-5.858-5.858h-6.071v5.858h6.071");
}

:global(.h0qgeuwow) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11.5a3 3 0 0 1 3-3h8.718a4 4 0 0 1 2.325.745l4.914 3.51a4 4 0 0 0 2.325.745H40.5a3 3 0 0 1 3 3v20a3 3 0 0 1-3 3h-33a3 3 0 0 1-3-3z");
}

</style>
