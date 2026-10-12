<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wdd_k9f2l"/><rect class="pw_pskbhp"/><path class="ixu7t3bpy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:battery-recycling" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ixu7t3bpy) {
  d: path("M11 5.25h2m-.4 5L11 13h2l-1.6 2.5");
}

:global(.pw_pskbhp) {
  width: 6px;
  height: 10px;
  x: 9px;
  y: 7.75px;
  rx: 1.5px;
}

:global(.wdd_k9f2l) {
  d: path("M16.5 4.21a9 9 0 1 1-9 0m-.65 2.42l.65-2.42l-2.42-.65");
}

</style>
