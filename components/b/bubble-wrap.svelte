<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="f7r42znre"/><path class="lv_qlocdw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bubble-wrap" {...props}></Icon>
<style>
:global(.f7r42znre) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lv_qlocdw) {
  d: path("M7.25 5.5a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5m9.5 0a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5M7.25 15a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5m9.5 0a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5M12 10.25a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5");
}

</style>
