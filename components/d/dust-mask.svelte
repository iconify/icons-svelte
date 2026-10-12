<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qxfqnabqx"/><circle class="e-6ytzbao"/><path class="vcluoubna"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dust-mask" {...props}></Icon>
<style>
:global(.e-6ytzbao) {
  cx: 12px;
  cy: 15px;
  r: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qxfqnabqx) {
  d: path("M4 11c2-2.5 5-3.5 8-3.5s6 1 8 3.5c-.5 4.5-4 8.5-8 9.5c-4-1-7.5-5-8-9.5m8-3.5v4");
}

:global(.vcluoubna) {
  d: path("M4 11c-.75-2.5-.25-5 1.75-7M20 11c.75-2.5.25-5-1.75-7");
}

</style>
