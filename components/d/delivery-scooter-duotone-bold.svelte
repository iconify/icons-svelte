<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jm23m7ozc"/><path class="cz1n--5fo"/><path class="mva-jqb3y"/><path class="yrmgu5-ry"/><path class="skyc_tbew"/><path class="db6bvvb_j"/><path class="olph5u3xh"/><path class="f6186achz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:delivery-scooter-duotone-bold" {...props}></Icon>
<style>
:global(.cz1n--5fo) {
  fill: currentColor;
  d: path("M16 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.db6bvvb_j) {
  d: path("M16 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.f6186achz) {
  d: path("M15 8h4");
}

:global(.jm23m7ozc) {
  fill: currentColor;
  d: path("M4 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mva-jqb3y) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 16 4 -4h5V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.olph5u3xh) {
  d: path("m8 16 4 -4h5V8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.skyc_tbew) {
  d: path("M4 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.yrmgu5-ry) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15 8h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
