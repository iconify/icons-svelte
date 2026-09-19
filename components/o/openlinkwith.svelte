<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lnp465b1q"/><path class="qlxycsb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:openlinkwith" {...props}></Icon>
<style>
:global(.lnp465b1q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.263 34.903a4.298 4.298 0 1 1-4.298 4.299a4.303 4.303 0 0 1 4.298-4.299M15.737 4.5a4.298 4.298 0 1 1-4.298 4.298A4.3 4.3 0 0 1 15.737 4.5m.658 30.403a4.298 4.298 0 1 1-4.29 4.299a4.3 4.3 0 0 1 4.29-4.299M32.263 4.5a4.298 4.298 0 1 1-4.298 4.298A4.3 4.3 0 0 1 32.263 4.5");
}

:global(.qlxycsb6b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.507 34.903c-.658-13.886-16.103-7.92-16.77-21.806m16.526 0c0 3.965-1.102 7.323-3.307 9.083M16.395 34.903c0-3.97.778-7.16 2.982-8.92");
}

</style>
