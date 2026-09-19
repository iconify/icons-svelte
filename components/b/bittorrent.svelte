<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="ftrtg_b4w"/><path class="ivnu1ra2k"/><path class="s-vb40stl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bittorrent" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ftrtg_b4w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.944 34.176h-22a8.12 8.12 0 1 1 5.741-13.861");
}

:global(.ivnu1ra2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.112 37.019H20.944c-6.055 0-10.962-4.908-10.962-10.963s4.907-10.962 10.962-10.962c1.486 0 2.903.296 4.196.832");
}

:global(.s-vb40stl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.515 39.86H20.944c-7.624 0-13.804-6.18-13.804-13.804s6.18-13.804 13.804-13.804");
}

</style>
