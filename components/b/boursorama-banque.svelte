<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="etfsozrby"/><path class="ju1ivmpdq"/><path class="sykp3folz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:boursorama-banque" {...props}></Icon>
<style>
:global(.etfsozrby) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.584 41.5a6 6 0 0 1-6-6v-17h-17a6 6 0 0 1 0-12h23a6 6 0 0 1 6 6v23a6 6 0 0 1-6 6");
}

:global(.ju1ivmpdq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.584 41.5a6 6 0 0 1-4.242-10.242l23-23a6 6 0 1 1 8.484 8.484l-23 23a5.98 5.98 0 0 1-4.242 1.758");
}

:global(.sykp3folz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.584 18.5v-6a6 6 0 0 1 6-6h0m-6 12h6a6 6 0 0 0 6-6h0");
}

</style>
