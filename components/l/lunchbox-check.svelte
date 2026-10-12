<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="tl0x8xoaa"/><path class="s4cr7mb6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lunchbox-check" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s4cr7mb6v) {
  d: path("M8.25 8.75v-2.5a2 2 0 0 1 2-2h3.5a2 2 0 0 1 2 2v2.5M2.75 13h18.5M12 13v2.75");
}

:global(.tl0x8xoaa) {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 8.75px;
  rx: 2.5px;
}

</style>
