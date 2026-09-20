<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o-us9ngaz"/><path class="avz09zu-i"/><path class="cm4k_7biz"/><path class="c_pe6njtz"/><path class="bzecsub_a"/><path class="ipr9vreed"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-left-to-line-duotone-thin" {...props}></Icon>
<style>
:global(.avz09zu-i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bzecsub_a) {
  d: path("M8 12h12");
}

:global(.c_pe6njtz) {
  d: path("M4 7v10");
}

:global(.cm4k_7biz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m12 8 -4 4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ipr9vreed) {
  d: path("m12 8 -4 4 4 4");
}

:global(.o-us9ngaz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
