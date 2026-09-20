<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="earhjk-cy"/><path class="z-znvccxj"/><path class="hf_gtezns"/><path class="zs71zpbwj"/><path class="xgrfb-bqu"/><path class="tee3b-ble"/><path class="xyj-l9cjp"/><path class="e4mg5wbxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:list-indent-increase-duotone-thin" {...props}></Icon>
<style>
:global(.e4mg5wbxb) {
  d: path("M3 9.5 5.5 12 3 14.5");
}

:global(.earhjk-cy) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hf_gtezns) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tee3b-ble) {
  d: path("M10 12h11");
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

:global(.z-znvccxj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zs71zpbwj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9.5 5.5 12 3 14.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
