<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jfmvsgbrx"/><path class="qvu-rvxsg"/><path class="biz7t_4gn"/><path class="p10_onbbz"/><path class="ojq3d2bwe"/><path class="ni-_lk7vs"/><path class="c3wl0l-ou"/><path class="lmzbshh9e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:checkpoint-save-duotone-thin" {...props}></Icon>
<style>
:global(.biz7t_4gn) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 13v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c3wl0l-ou) {
  d: path("M19 13v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jfmvsgbrx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lmzbshh9e) {
  d: path("M16.5 16.5 19 19l2.5 -2.5");
}

:global(.ni-_lk7vs) {
  d: path("M5 5h10v6H5");
}

:global(.ojq3d2bwe) {
  d: path("M5 3v18");
}

:global(.p10_onbbz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16.5 16.5 19 19l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qvu-rvxsg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 5h10v6H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
