<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r8a9qcmsq"/><path class="hj8glsj2p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:clock-in" {...props}></Icon>
<style>
:global(.hj8glsj2p) {
  d: path("M10.5 6.5v4h3M18 15v6m-2.5-2.5L18 21l2.5-2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.r8a9qcmsq) {
  d: path("M11.154 17.971a7.5 7.5 0 1 1 6.817-6.817");
}

</style>
