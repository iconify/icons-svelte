<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khksl7boy"/><path class="n45vxib8e"/><path class="bxojdxbnt"/><path class="xgrfb-bqu"/><path class="x22av82oi"/><path class="cn-9z7b7f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:align-left-duotone-bold" {...props}></Icon>
<style>
:global(.bxojdxbnt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 18h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cn-9z7b7f) {
  d: path("M3 18h15");
}

:global(.khksl7boy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n45vxib8e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x22av82oi) {
  d: path("M3 12h11");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

</style>
