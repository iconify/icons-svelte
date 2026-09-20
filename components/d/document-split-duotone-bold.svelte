<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="itaf_r5rq"/><path class="lfxy7bcmb"/><path class="bp9na9-yx"/><path class="vl0d0wtss"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:document-split-duotone-bold" {...props}></Icon>
<style>
:global(.bp9na9-yx) {
  d: path("M10 3H4v16h6");
}

:global(.itaf_r5rq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 3H4v16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lfxy7bcmb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 5h6v16h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vl0d0wtss) {
  d: path("M14 5h6v16h-6");
}

</style>
