<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kf3muskvz"/><path class="wgplwsbmx"/><path class="vqal-abhe"/><path class="bpdfs5b6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:health-probe-duotone-thin" {...props}></Icon>
<style>
:global(.bpdfs5b6a) {
  d: path("m9 15 2 2 4 -4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kf3muskvz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h4.5l2 -2 4 4 2 -2H21");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vqal-abhe) {
  d: path("M3 8h4.5l2 -2 4 4 2 -2H21");
}

:global(.wgplwsbmx) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9 15 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
