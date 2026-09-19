<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h54fp9b-c"/><path class="c8iz87bew"/><path class="kdnmf5b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:finanzassistent" {...props}></Icon>
<style>
:global(.c8iz87bew) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.67 35.42h9.68c0-8.58 11.16-18 11.9-18H28.43");
}

:global(.h54fp9b-c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.6 36.87c0-12.29 16-25.74 17-25.74H20.1c-2 0-15.6 13.45-15.6 25.74Z");
}

:global(.kdnmf5b7o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.43 34.14h6.69c0-6 7.85-12.67 8.38-12.67h-7.85");
}

</style>
