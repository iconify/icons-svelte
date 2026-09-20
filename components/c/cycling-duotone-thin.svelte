<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t7fcj43nv"/><path class="ic_pehd5a"/><path class="ziznm1ama"/><path class="xob7qnbfo"/><path class="uk-flc9on"/><path class="jlfjgzbqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cycling-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.jlfjgzbqx) {
  d: path("M9 9h6");
}

:global(.t7fcj43nv) {
  fill: currentColor;
  d: path("M14 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.uk-flc9on) {
  d: path("M5 5h7");
}

:global(.xob7qnbfo) {
  d: path("M9 17V5");
}

:global(.ziznm1ama) {
  d: path("M14 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
