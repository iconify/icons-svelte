<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j9sg938ez"/><path class="aw_23kbkp"/><path class="kbulryb2v"/><path class="zqnqkr2ls"/><path class="z_leajngu"/><path class="ptvhb3bfe"/><path class="b8xluzc6p"/><path class="v6f1oidhi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:collapse-duotone-regular" {...props}></Icon>
<style>
:global(.aw_23kbkp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 10 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.b8xluzc6p) {
  d: path("M14 20v-6h6");
}

:global(.j9sg938ez) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 4v6H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kbulryb2v) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 20v-6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ptvhb3bfe) {
  d: path("M10 10 4 4");
}

:global(.v6f1oidhi) {
  d: path("m14 14 6 6");
}

:global(.z_leajngu) {
  d: path("M10 4v6H4");
}

:global(.zqnqkr2ls) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m14 14 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
