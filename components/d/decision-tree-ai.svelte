<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tbgp-kb2l"/><rect class="vd153n31u"/><rect class="y7a80dsxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:decision-tree-ai" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tbgp-kb2l) {
  d: path("m12.57 3.32l2.61 2.61q.57.57 0 1.14l-2.61 2.61q-.57.57-1.14 0L8.82 7.07q-.57-.57 0-1.14l2.61-2.61q.57-.57 1.14 0M12 10.25v2.25m-6 2.75V12.5h12v2.75");
}

:global(.vd153n31u) {
  width: 6.5px;
  height: 6px;
  x: 2.75px;
  y: 15.25px;
  rx: 1.75px;
}

:global(.y7a80dsxw) {
  width: 6.5px;
  height: 6px;
  x: 14.75px;
  y: 15.25px;
  rx: 1.75px;
}

</style>
