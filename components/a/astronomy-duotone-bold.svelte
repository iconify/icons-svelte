<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dstagacts"/><path class="arox4o3qw"/><path class="ik6mh31gy"/><path class="gv5aqrbwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:astronomy-duotone-bold" {...props}></Icon>
<style>
:global(.arox4o3qw) {
  d: path("m5 12 8 -8 4 4 -8 8Z");
}

:global(.dstagacts) {
  fill: currentColor;
  d: path("m5 12 8 -8 4 4 -8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gv5aqrbwu) {
  d: path("M7 21h8");
}

:global(.ik6mh31gy) {
  d: path("M11 14v7");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
