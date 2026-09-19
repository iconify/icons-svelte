<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tgfm5hyhh"/><path class="hzpqnlmob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:luxtrust-mobile" {...props}></Icon>
<style>
:global(.hzpqnlmob) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4");
}

:global(.tgfm5hyhh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.5 16.1v15.65h7.851m1-15.688H34.5m-5.535.134v15.742");
}

</style>
