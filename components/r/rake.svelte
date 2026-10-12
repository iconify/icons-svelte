<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pjokakbyf"/><rect class="hvc_w_9lp"/><path class="aqzeatbnz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rake" {...props}></Icon>
<style>
:global(.aqzeatbnz) {
  d: path("M6 15.75v5.5m4-5.5v5.5m4-5.5v5.5m4-5.5v5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hvc_w_9lp) {
  width: 15.5px;
  height: 3px;
  x: 4.25px;
  y: 12.75px;
  rx: 1.5px;
}

:global(.pjokakbyf) {
  d: path("M12 2.75v10");
}

</style>
