<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nvkv6bbso"/><path class="yc8p4mb1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dept-produce-sign" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nvkv6bbso) {
  d: path("M6.5 9.5h11A3.5 3.5 0 0 1 21 13v4.5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17.5V13a3.5 3.5 0 0 1 3.5-3.5m.5-7v7m10-7v7");
}

:global(.yc8p4mb1k) {
  d: path("M9 18.25c0-4.25 2.5-6 6-6c0 3.75-2.5 6-6 6m0 0l3.5-3.5");
}

</style>
