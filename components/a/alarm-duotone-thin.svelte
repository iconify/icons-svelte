<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pw3t53bda"/><path class="nqda50bqs"/><path class="wsg9rhonx"/><path class="md_wm9bov"/><path class="n7tvrlb7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:alarm-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.md_wm9bov) {
  d: path("m3 6 3 -3");
}

:global(.n7tvrlb7x) {
  d: path("m21 6 -3 -3");
}

:global(.nqda50bqs) {
  d: path("M4 13a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

:global(.pw3t53bda) {
  fill: currentColor;
  d: path("M4 13a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.wsg9rhonx) {
  d: path("M12 8v5h4");
}

</style>
