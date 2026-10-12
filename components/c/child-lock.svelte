<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="kqp8bdpkm"/><path class="s4pokskin"/><rect class="lkh5fbc6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:child-lock" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kqp8bdpkm) {
  width: 17px;
  height: 18.5px;
  x: 3.5px;
  y: 2.75px;
  rx: 2px;
}

:global(.lkh5fbc6f) {
  width: 6px;
  height: 5px;
  x: 9px;
  y: 11.5px;
  rx: 1.5px;
}

:global(.s4pokskin) {
  d: path("M12 2.75V5.5m0 12.75v3m-1.75-9.75V9.75a1.75 1.75 0 0 1 3.5 0v1.75");
}

</style>
