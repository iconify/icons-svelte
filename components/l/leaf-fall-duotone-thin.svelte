<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sg5tbcboo"/><path class="fzx2-xbbx"/><path class="vi0rmgvkt"/><path class="d5ewpzb2a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:leaf-fall-duotone-thin" {...props}></Icon>
<style>
:global(.d5ewpzb2a) {
  d: path("M12 20c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
}

:global(.fzx2-xbbx) {
  fill: currentColor;
  d: path("M12 20c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sg5tbcboo) {
  fill: currentColor;
  d: path("M4 11c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.vi0rmgvkt) {
  d: path("M4 11c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
}

</style>
