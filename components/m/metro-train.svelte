<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hvkmgeb3s"/><rect class="sio8s-ban"/><path class="q5e6q08zg"/><circle class="lsh48acyg"/><circle class="jgdawjjhh"/><path class="f-9e4rrar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:metro-train" {...props}></Icon>
<style>
:global(.f-9e4rrar) {
  d: path("M2.75 20.75h18.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hvkmgeb3s) {
  d: path("m8 6.75l2-2.5h4");
}

:global(.jgdawjjhh) {
  cx: 17px;
  cy: 18px;
  r: 1.25px;
}

:global(.lsh48acyg) {
  cx: 7px;
  cy: 18px;
  r: 1.25px;
}

:global(.q5e6q08zg) {
  d: path("M5.5 9.75h3m2.25 0h2.5m2.25 0h3m-15.75 3.5h18.5");
}

:global(.sio8s-ban) {
  width: 18.5px;
  height: 10px;
  x: 2.75px;
  y: 6.75px;
  rx: 1.5px;
}

</style>
