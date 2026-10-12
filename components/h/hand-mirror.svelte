<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="isrvbeblh"/><rect class="v9bwdibxc"/><path class="kwfexccqg"/><path class="aft_a8bju"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hand-mirror" {...props}></Icon>
<style>
:global(.aft_a8bju) {
  d: path("M10.75 9.25A1.25 1.25 0 0 1 12 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.isrvbeblh) {
  d: path("M12 2.75a5.75 5.25 0 1 1 0 10.5a5.75 5.25 0 1 1 0-10.5");
}

:global(.kwfexccqg) {
  d: path("M12 5.25a3.25 2.75 0 1 1 0 5.5a3.25 2.75 0 1 1 0-5.5");
}

:global(.v9bwdibxc) {
  width: 2.5px;
  height: 7.5px;
  x: 10.75px;
  y: 13.75px;
  rx: 1.25px;
}

</style>
