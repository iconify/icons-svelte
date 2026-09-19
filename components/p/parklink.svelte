<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hzpqnlmob"/><path class="tdejo1l7v"/><circle class="avxqhobsp"/><circle class="k2wg1dafr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:parklink" {...props}></Icon>
<style>
:global(.avxqhobsp) {
  cx: 27.142px;
  cy: 16.887px;
  r: 2.581px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.hzpqnlmob) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4");
}

:global(.k2wg1dafr) {
  cx: 18.503px;
  cy: 16.887px;
  r: 2.581px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tdejo1l7v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36 22.725c0 7.162-5.806 12.968-12.969 12.968A12.96 12.96 0 0 1 12 29.547");
}

</style>
