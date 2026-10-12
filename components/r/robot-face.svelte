<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="i4fqodbwn"/><rect class="kkeq7-bob"/><rect class="g_u9p_b6y"/><rect class="ydbcdi_tx"/><path class="fvpssjb1y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:robot-face" {...props}></Icon>
<style>
:global(.fvpssjb1y) {
  d: path("M10.75 14.25V17m2.5-2.75V17");
}

:global(.g_u9p_b6y) {
  width: 3.25px;
  height: 3px;
  x: 13.75px;
  y: 8.75px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i4fqodbwn) {
  width: 17.5px;
  height: 15.5px;
  x: 3.25px;
  y: 4.25px;
  rx: 4.5px;
}

:global(.kkeq7-bob) {
  width: 3.25px;
  height: 3px;
  x: 7px;
  y: 8.75px;
  rx: 1px;
}

:global(.ydbcdi_tx) {
  width: 8px;
  height: 2.75px;
  x: 8px;
  y: 14.25px;
  rx: 1px;
}

</style>
