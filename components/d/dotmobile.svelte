<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yypc16btt"/><path class="atu45yblr"/><path class="zo9c_tbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dotmobile" {...props}></Icon>
<style>
:global(.atu45yblr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.153 42.56a21.498 21.498 0 1 1 22.009-.188");
}

:global(.yypc16btt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.157 35.113a12.285 12.285 0 1 1 11.89-.112");
}

:global(.zo9c_tbyt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.784 28.63a4.915 4.915 0 1 1 .481.228");
}

</style>
