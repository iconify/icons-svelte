<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oi9g91b_q"/><path class="b-af79bpy"/><path class="hk8a83bva"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pond-duotone-bold" {...props}></Icon>
<style>
:global(.b-af79bpy) {
  d: path("M12 7c5 0 9 2 9 6s-4 6 -9 6 -9 -2 -9 -6 4 -6 9 -6");
}

:global(.hk8a83bva) {
  d: path("M8 15c2 -2 6 -2 8 0");
}

:global(.oi9g91b_q) {
  fill: currentColor;
  d: path("M12 7c5 0 9 2 9 6s-4 6 -9 6 -9 -2 -9 -6 4 -6 9 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
