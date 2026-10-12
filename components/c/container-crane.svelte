<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i03tn_bow"/><rect class="hu0hktgia"/><path class="kg__uyb9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:container-crane" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hu0hktgia) {
  width: 6.5px;
  height: 4.75px;
  x: 13.75px;
  y: 11.75px;
  rx: 0.75px;
}

:global(.i03tn_bow) {
  d: path("M5 21.25V5m5.5 16.25V5M2.75 5h18.5M5 13l5.5-8M5 13h5.5M17 5v6");
}

:global(.kg__uyb9b) {
  d: path("M17 11.75v4.75");
}

</style>
