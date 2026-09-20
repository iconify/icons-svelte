<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="iafbhe10i"/><path class="ttbnd_bgh"/><path class="k6t-okb_f"/><path class="urk2115hi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:object-duotone-bold" {...props}></Icon>
<style>
:global(.iafbhe10i) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 4 7 6v4l-2 2 2 2v4l2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k6t-okb_f) {
  d: path("M9 4 7 6v4l-2 2 2 2v4l2 2");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ttbnd_bgh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 4 2 2v4l2 2 -2 2v4l-2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.urk2115hi) {
  d: path("m15 4 2 2v4l2 2 -2 2v4l-2 2");
}

</style>
