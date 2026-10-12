<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="d7lirwbtl"/><path class="m-unrvbfc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:monitoring-ai" {...props}></Icon>
<style>
:global(.d7lirwbtl) {
  width: 18.5px;
  height: 13px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m-unrvbfc) {
  d: path("M5.5 10.5h1.75l1.5-2.75l2.5 5.5l1.5-2.75h.75M17 7q.33 2.42 2.75 2.75q-2.42.33-2.75 2.75q-.33-2.42-2.75-2.75Q16.67 9.42 17 7m-5 9.75v4m-3.5 0h7");
}

</style>
