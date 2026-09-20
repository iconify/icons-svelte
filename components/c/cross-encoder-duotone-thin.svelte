<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n8njab91k"/><path class="enbfn3bgm"/><path class="upcu0wmvf"/><path class="m1u46ab5m"/><path class="sz5he4mqt"/><path class="gig9ivbwc"/><path class="kfs1394gk"/><path class="z5135gcut"/><path class="ba_a_obvy"/><path class="rzfubwb2e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cross-encoder-duotone-thin" {...props}></Icon>
<style>
:global(.ba_a_obvy) {
  d: path("m8 16 4 -4");
}

:global(.enbfn3bgm) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gig9ivbwc) {
  d: path("M2 8h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kfs1394gk) {
  d: path("M2 16h6");
}

:global(.m1u46ab5m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 16 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n8njab91k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rzfubwb2e) {
  d: path("M12 12h10");
}

:global(.sz5he4mqt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.upcu0wmvf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 8 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z5135gcut) {
  d: path("m8 8 4 4");
}

</style>
