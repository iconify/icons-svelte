<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m_2lqo6nk"/><circle class="zz80vlb7c"/><path class="rbvsij3wx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mirrorless-camera" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m_2lqo6nk) {
  d: path("M3.75 7.5zq1 0 1.5-1.37q.5-1.38 2.5-1.38h.5q2 0 2.5 1.38q.5 1.37 2.5 1.37h6q2 0 2 2v7.75q0 2-2 2H4.75q-2 0-2-2V9.5q0-2 1-2");
}

:global(.rbvsij3wx) {
  d: path("M16.75 7.5v11.75");
}

:global(.zz80vlb7c) {
  cx: 9.25px;
  cy: 13.25px;
  r: 3.5px;
}

</style>
