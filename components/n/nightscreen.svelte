<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="putlpfzxr"/><path class="bf-8y0jyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nightscreen" {...props}></Icon>
<style>
:global(.bf-8y0jyk) {
  fill: none;
  stroke: currentColor;
  d: path("M23 16.06a8.46 8.46 0 0 0-4.54 1.29h.06A8.37 8.37 0 0 1 21 29a8.4 8.4 0 0 1-2.58 2.56a8.38 8.38 0 0 0 9-14.14A8.34 8.34 0 0 0 23 16.06Z");
}

:global(.putlpfzxr) {
  fill: none;
  stroke: currentColor;
  d: path("m24 3.38l6.23 6.22h7.82v8.66L43.82 24l-5.65 5.65v8.85h-8.25l-5.85 5.85l-5.56-5.56H10v-8.7l-5.93-5.85l6.1-6.1V9.73h7.9Z");
}

</style>
