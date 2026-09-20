<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m1sxkkbgc"/><path class="cbq8-eboh"/><path class="rrw43cnoe"/><path class="dotyiqbdy"/><path class="et-iwmblh"/><path class="wg1ykyaxv"/><path class="rc8xkcb_g"/><path class="qitpg1b_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:double-bed-duotone-bold" {...props}></Icon>
<style>
:global(.cbq8-eboh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 14.5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dotyiqbdy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 11V8h5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.et-iwmblh) {
  d: path("M2 18v-7h20v7");
}

:global(.m1sxkkbgc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 18v-7h20v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qitpg1b_y) {
  d: path("M13 11V8h5v3");
}

:global(.rc8xkcb_g) {
  d: path("M4 11V8h5v3");
}

:global(.rrw43cnoe) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 11V8h5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wg1ykyaxv) {
  d: path("M2 14.5h20");
}

</style>
