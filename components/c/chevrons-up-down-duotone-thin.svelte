<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w-w1bacyu"/><path class="m3dr_ybtq"/><path class="caznxbcdb"/><path class="ag27qibsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevrons-up-down-duotone-thin" {...props}></Icon>
<style>
:global(.ag27qibsz) {
  d: path("m7 15 5 5 5 -5");
}

:global(.caznxbcdb) {
  d: path("m7 9 5 -5 5 5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m3dr_ybtq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 15 5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w-w1bacyu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 9 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
