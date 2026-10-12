<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_-q_pb0z"/><circle class="w7-glrb_d"/><path class="p0wu51vaj"/><circle class="v_u09sohe"/><path class="dlqe2221s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:poll-vote" {...props}></Icon>
<style>
:global(.a_-q_pb0z) {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 3px;
}

:global(.dlqe2221s) {
  d: path("M11.5 15.5h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p0wu51vaj) {
  d: path("M11.5 8.5H17");
}

:global(.v_u09sohe) {
  cx: 7.75px;
  cy: 15.5px;
  r: 1.75px;
}

:global(.w7-glrb_d) {
  cx: 7.75px;
  cy: 8.5px;
  r: 1.75px;
}

</style>
