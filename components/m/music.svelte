<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v89m_cccs"/><circle class="t9jw750lp"/><circle class="w1qs9fdcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:music" {...props}></Icon>
<style>
:global(.t9jw750lp) {
  cx: 11.45px;
  cy: 37.74px;
  r: 5.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.v89m_cccs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m42.31 13.38l-25.1 3.48V7.98l25.1-3.48zm0 0v17.15m-25.1-13.67v20.88");
}

:global(.w1qs9fdcc) {
  cx: 36.55px;
  cy: 30.53px;
  r: 5.76px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
