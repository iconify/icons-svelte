<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="f9xu_cb8q"/><circle class="dxajnmbvk"/><circle class="tyhetpb4e"/><path class="h4z-n8bhd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:git-fork" {...props}></Icon>
<style>
:global(.dxajnmbvk) {
  cx: 17.5px;
  cy: 5.25px;
  r: 2.25px;
}

:global(.f9xu_cb8q) {
  cx: 6.5px;
  cy: 5.25px;
  r: 2.25px;
}

:global(.h4z-n8bhd) {
  d: path("M6.5 7.5v1.75a2.5 2.5 0 0 0 2.5 2.5h6a2.5 2.5 0 0 0 2.5-2.5V7.5M12 11.75v4.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tyhetpb4e) {
  cx: 12px;
  cy: 18.75px;
  r: 2.25px;
}

</style>
