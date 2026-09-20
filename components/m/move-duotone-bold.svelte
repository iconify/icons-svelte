<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b6e35tlvq"/><path class="ebvczzbhc"/><path class="vj17dpbln"/><path class="zh6q_cf_u"/><path class="k4wqseaqs"/><path class="t_57glb-y"/><path class="r7xk8o29f"/><path class="sxlwlmkmh"/><path class="t407nkbfi"/><path class="qrqk-5btd"/><path class="cu_n5qbwp"/><path class="mi_m6achy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:move-duotone-bold" {...props}></Icon>
<style>
:global(.b6e35tlvq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cu_n5qbwp) {
  d: path("m7 9 -3 3 3 3");
}

:global(.ebvczzbhc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k4wqseaqs) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m7 9 -3 3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mi_m6achy) {
  d: path("m17 9 3 3 -3 3");
}

:global(.qrqk-5btd) {
  d: path("m9 17 3 3 3 -3");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.sxlwlmkmh) {
  d: path("M4 12h16");
}

:global(.t_57glb-y) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m17 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t407nkbfi) {
  d: path("m9 7 3 -3 3 3");
}

:global(.vj17dpbln) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 7 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zh6q_cf_u) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 17 3 3 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
