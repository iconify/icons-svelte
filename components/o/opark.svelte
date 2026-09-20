<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gn6v4rbhu"/><path class="s_uc42bjm"/><path class="b-455xbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:opark" {...props}></Icon>
<style>
:global(.b-455xbvw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.002 32.768A9.3 9.3 0 1 1 36.4 24a15.5 15.5 0 0 1-12.344 15.175");
}

:global(.gn6v4rbhu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.056 39.174a15.499 15.499 0 1 1-.101-30.369");
}

:global(.s_uc42bjm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.028 15.242A9.3 9.3 0 1 1 11.6 24.001a15.5 15.5 0 0 1 27.795-9.436a15.5 15.5 0 0 1-15.399 24.62");
}

</style>
