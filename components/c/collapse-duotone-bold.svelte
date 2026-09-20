<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u2zam5btq"/><path class="e2e5jtb6o"/><path class="ibxltbbey"/><path class="jccaajtgs"/><path class="z_leajngu"/><path class="ptvhb3bfe"/><path class="b8xluzc6p"/><path class="v6f1oidhi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:collapse-duotone-bold" {...props}></Icon>
<style>
:global(.b8xluzc6p) {
  d: path("M14 20v-6h6");
}

:global(.e2e5jtb6o) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 10 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ibxltbbey) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 20v-6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jccaajtgs) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 14 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ptvhb3bfe) {
  d: path("M10 10 4 4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u2zam5btq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 4v6H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v6f1oidhi) {
  d: path("m14 14 6 6");
}

:global(.z_leajngu) {
  d: path("M10 4v6H4");
}

</style>
