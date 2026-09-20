<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lppzsmemb"/><path class="utlpmrn-a"/><path class="m557ps9ux"/><path class="flscefshg"/><path class="irf6xy5kk"/><path class="x50q_4bdr"/><path class="i7iskytip"/><path class="ege_q3bkn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gift-open-duotone-bold" {...props}></Icon>
<style>
:global(.ege_q3bkn) {
  d: path("m8 5 2 -2");
}

:global(.flscefshg) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 5 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i7iskytip) {
  d: path("m13 6 3 -3");
}

:global(.irf6xy5kk) {
  d: path("M5 13v8h14v-8");
}

:global(.lppzsmemb) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 13v8h14v-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.m557ps9ux) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 6 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.utlpmrn-a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 10h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

</style>
