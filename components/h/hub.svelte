<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b_sk-j7xv"/><path class="sr_gdzbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hub" {...props}></Icon>
<style>
:global(.b_sk-j7xv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.74 31.29v3.77a1.64 1.64 0 0 0 1.71 1.57h20.22l6.93 6.24v-6.24h2.19a1.64 1.64 0 0 0 1.71-1.57V16.37a1.64 1.64 0 0 0-1.71-1.58h-3.92");
}

:global(.sr_gdzbnb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.18 8.55a1.68 1.68 0 0 0-1.68 1.68h0v19.38a1.68 1.68 0 0 0 1.68 1.68h30a1.69 1.69 0 0 0 1.69-1.67h0V10.24a1.69 1.69 0 0 0-1.68-1.69h-30Zm28.42 3.26l-13.42 9.88l-13.42-9.88");
}

</style>
