<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="k0bjsebqo"/><path class="o6bxdibgr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hall-pass" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k0bjsebqo) {
  width: 13.5px;
  height: 12.5px;
  x: 5.25px;
  y: 8.75px;
  rx: 2.5px;
}

:global(.o6bxdibgr) {
  d: path("M12 8.75C9.25 7.5 9.5 3 12 3s2.75 4.5 0 5.75M8.75 15h6.5m-2.5-2.5l2.5 2.5l-2.5 2.5");
}

</style>
