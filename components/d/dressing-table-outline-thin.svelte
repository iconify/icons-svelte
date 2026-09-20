<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="njnz25bwe"/><path class="bx3fv3b8c"/><path class="pmuiqo95v"/><path class="vdy_x0b6n"/><path class="oquq7bbql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dressing-table-outline-thin" {...props}></Icon>
<style>
:global(.bx3fv3b8c) {
  d: path("M12 13v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.njnz25bwe) {
  d: path("M8 8a4 5 0 1 1 8 0 4 5 0 1 1 -8 0");
}

:global(.oquq7bbql) {
  d: path("M20 17v4");
}

:global(.pmuiqo95v) {
  d: path("M2 17h20");
}

:global(.vdy_x0b6n) {
  d: path("M4 17v4");
}

</style>
