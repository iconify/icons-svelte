<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ypj59n15n"/><path class="xid91tbpa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ceiling-hanging-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xid91tbpa) {
  d: path("m13.75 11l2.75 2.75l-2.75 2.75");
}

:global(.ypj59n15n) {
  d: path("M2.5 2.5h19M6 2.5v6m12-6v6m-12 0h12a3.5 3.5 0 0 1 3.5 3.5v3.5A3.5 3.5 0 0 1 18 19H6a3.5 3.5 0 0 1-3.5-3.5V12A3.5 3.5 0 0 1 6 8.5m1 5.25h9.5");
}

</style>
