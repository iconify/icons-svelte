<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="n6-bn0bqx"/><circle class="k0a36_yae"/><path class="p6vfrcxbc"/><path class="znlnqjb3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:revenue-stream" {...props}></Icon>
<style>
:global(.k0a36_yae) {
  cx: 12px;
  cy: 15.75px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n6-bn0bqx) {
  width: 18.5px;
  height: 11px;
  x: 2.75px;
  y: 10.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

:global(.p6vfrcxbc) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 15.75h.01m10.99 0h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.znlnqjb3d) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.75v-5m-3 3l3-3l3 3");
}

</style>
