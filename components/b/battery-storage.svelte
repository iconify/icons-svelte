<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="g_zb3raan"/><path class="e1sqnpbpy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:battery-storage" {...props}></Icon>
<style>
:global(.e1sqnpbpy) {
  d: path("M5.75 6.25v-2.5M12 6.25v-2.5m6.25 2.5v-2.5m-9.33 2.5v15m6.16-15v15M12.75 10.5L11 13.75h2L11.25 17");
}

:global(.g_zb3raan) {
  width: 18.5px;
  height: 15px;
  x: 2.75px;
  y: 6.25px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
