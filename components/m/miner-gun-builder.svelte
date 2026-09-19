<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xonx9sy-j"/><circle class="fturw2a6a"/><circle class="va5lok6xx"/><circle class="x8zz9w6uw"/><circle class="sdqby7e8u"/><path class="wpzfacbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:miner-gun-builder" {...props}></Icon>
<style>
:global(.fturw2a6a) {
  cx: 38.5px;
  cy: 37.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.sdqby7e8u) {
  cx: 37.5px;
  cy: 24px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.va5lok6xx) {
  cx: 24px;
  cy: 22px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wpzfacbzi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.632 10.302l-4.765 9.896m1.111 2.095l9.543 1.414m2.127 2.287l.704 9.511");
}

:global(.x8zz9w6uw) {
  cx: 30.5px;
  cy: 8.5px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xonx9sy-j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.5 5.5h10v10h-10zm0 13.5h10v10h-10zm0 13.5h10v10h-10zm13.5 0h10v10H21z");
}

</style>
