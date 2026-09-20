<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cphlk2bgi"/><path class="zy54a7bml"/><path class="t7ql4f28h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:moving-day-outline-thin" {...props}></Icon>
<style>
:global(.cphlk2bgi) {
  d: path("M3 19v-7l6 -6 6 6v7Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t7ql4f28h) {
  d: path("m19 10 2 2 -2 2");
}

:global(.zy54a7bml) {
  d: path("M17 12h4");
}

</style>
