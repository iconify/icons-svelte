<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jt-rzwblh"/><path class="cphlk2bgi"/><path class="zy54a7bml"/><path class="t7ql4f28h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:moving-day-duotone-regular" {...props}></Icon>
<style>
:global(.cphlk2bgi) {
  d: path("M3 19v-7l6 -6 6 6v7Z");
}

:global(.jt-rzwblh) {
  fill: currentColor;
  d: path("M3 19v-7l6 -6 6 6v7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t7ql4f28h) {
  d: path("m19 10 2 2 -2 2");
}

:global(.zy54a7bml) {
  d: path("M17 12h4");
}

</style>
