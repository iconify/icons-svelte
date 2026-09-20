<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="pk7qwlbxv"/><path class="tjc2w5b3m"/><path class="byyzkjuye"/><path class="quu8uycwi"/><path class="j4ecinbzh"/><path class="er6s1rc2j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:prewarm-pool-duotone-bold" {...props}></Icon>
<style>
:global(.byyzkjuye) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 11 2 -2 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.er6s1rc2j) {
  d: path("m15 11 2 -2 -2 -2");
}

:global(.j4ecinbzh) {
  d: path("m9 11 2 -2 -2 -2");
}

:global(.pk7qwlbxv) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 14v5h18v-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.quu8uycwi) {
  d: path("M3 14v5h18v-5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tjc2w5b3m) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 11 2 -2 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
