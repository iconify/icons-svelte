<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a1-b9_bdl"/><path class="g4fb1zbjj"/><path class="k15p1lb3a"/><path class="mbgtdkbsk"/><path class="flblq5ico"/><path class="zsil77j-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lightning-bolt-duotone-thin" {...props}></Icon>
<style>
:global(.a1-b9_bdl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 2 -8 8h5l-8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.flblq5ico) {
  d: path("m13 14 6 6");
}

:global(.g4fb1zbjj) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m13 14 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k15p1lb3a) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m19 14 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mbgtdkbsk) {
  d: path("m16 2 -8 8h5l-8 8");
}

:global(.zsil77j-s) {
  d: path("m19 14 -6 6");
}

</style>
