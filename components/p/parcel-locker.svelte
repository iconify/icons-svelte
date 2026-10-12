<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hoi44xq4a"/><path class="g7gikz6ze"/><rect class="buevg_brm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:parcel-locker" {...props}></Icon>
<style>
:global(.buevg_brm) {
  width: 4.25px;
  height: 4.5px;
  x: 14.5px;
  y: 5.25px;
  rx: 0.75px;
}

:global(.g7gikz6ze) {
  d: path("M12 2.75v18.5M2.75 9H12m-9.25 6H12m0-2.25h9.25m-11.75-7v.5m0 5.5v.5m0 5.5v.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hoi44xq4a) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
