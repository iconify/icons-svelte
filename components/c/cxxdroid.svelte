<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n1uvvwbdw"/><circle class="cpk0fnbgt"/><path class="skxgjkfvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cxxdroid" {...props}></Icon>
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

:global(.n1uvvwbdw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.642 21.288l-4 5.3m-9.819.239a5.713 5.713 0 0 1-5.816 5.653h0a5.713 5.713 0 0 1-5.816-5.653v-5.654a5.713 5.713 0 0 1 5.816-5.653h0a5.53 5.53 0 0 1 5.6 5.653h0m6.98.039l-4 5.3m4 0l-4-5.3m11.222 5.3l-4-5.3");
}

:global(.skxgjkfvm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.764 4.373v8.555a2 2 0 0 0 2 2h8.724A21.5 21.5 0 0 0 32.764 4.373");
}

</style>
