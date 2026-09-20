<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k9jn2o-zp"/><path class="k9on3tb9k"/><path class="vgy66lb4b"/><path class="fvt2-0orr"/><path class="u4sowhi7h"/><path class="xslfg2evh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cold-snap-duotone-bold" {...props}></Icon>
<style>
:global(.fvt2-0orr) {
  d: path("M12 4v8m-4 0 8 -8");
}

:global(.k9jn2o-zp) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v8m-4 0 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k9on3tb9k) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 16h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u4sowhi7h) {
  d: path("M4 16h16");
}

:global(.vgy66lb4b) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 21h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xslfg2evh) {
  d: path("M6 21h12");
}

</style>
