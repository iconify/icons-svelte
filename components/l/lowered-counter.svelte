<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="yak93r6mg"/><rect class="d1brzo6os"/><path class="pidrmzb1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lowered-counter" {...props}></Icon>
<style>
:global(.d1brzo6os) {
  width: 10px;
  height: 2.5px;
  x: 11.25px;
  y: 12.25px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pidrmzb1u) {
  d: path("M4.75 9.75v11.5m14.5-6.5v6.5m-3-18.5v5.5m-2-2l2 2l2-2");
}

:global(.yak93r6mg) {
  width: 8.5px;
  height: 2.5px;
  x: 2.75px;
  y: 7.25px;
  rx: 1px;
}

</style>
