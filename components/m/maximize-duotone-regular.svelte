<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hi5apkbez"/><path class="t_is_349d"/><path class="mr6kawbgx"/><path class="ku-b58bkm"/><path class="l6e2wzbuh"/><path class="qtj-xccdg"/><path class="ne_b8wtyo"/><path class="fsv7g_bbj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:maximize-duotone-regular" {...props}></Icon>
<style>
:global(.fsv7g_bbj) {
  d: path("M9 21H3v-6");
}

:global(.hi5apkbez) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 9V3h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ku-b58bkm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 21H3v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.l6e2wzbuh) {
  d: path("M3 9V3h6");
}

:global(.mr6kawbgx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 15v6h-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ne_b8wtyo) {
  d: path("M21 15v6h-6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qtj-xccdg) {
  d: path("M15 3h6v6");
}

:global(.t_is_349d) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 3h6v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
