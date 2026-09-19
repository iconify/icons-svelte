<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w6vd3nhfw"/><path class="i_ssevbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hyper-bridge" {...props}></Icon>
<style>
:global(.i_ssevbtb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.008 15.289a11.7 11.7 0 0 0-3.908 8.71a11.7 11.7 0 0 0 3.9 8.704A11.7 11.7 0 0 0 27.9 24a11.7 11.7 0 0 0-3.892-8.711");
}

:global(.w6vd3nhfw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.494 34.883a11.7 11.7 0 0 1-4.294.817A11.7 11.7 0 0 1 4.5 24a11.7 11.7 0 0 1 11.7-11.7a11.7 11.7 0 0 1 4.3.819m7.016-.006a11.7 11.7 0 0 1 4.285-.813A11.7 11.7 0 0 1 43.5 24a11.7 11.7 0 0 1-11.7 11.7a11.7 11.7 0 0 1-4.295-.816");
}

</style>
