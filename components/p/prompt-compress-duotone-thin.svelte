<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k5rjwjbvb"/><path class="lzc28-gln"/><path class="n2wl7ftpz"/><path class="n74dvacdd"/><path class="v9il_wb-q"/><path class="dznv025mt"/><path class="edr2cqsrt"/><path class="sz5hq9bxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:prompt-compress-duotone-thin" {...props}></Icon>
<style>
:global(.dznv025mt) {
  d: path("M6 14h12");
}

:global(.edr2cqsrt) {
  d: path("M9.5 3 12 5.5 14.5 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k5rjwjbvb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 10h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lzc28-gln) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n2wl7ftpz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 3 12 5.5 14.5 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n74dvacdd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 21 2.5 -2.5 2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sz5hq9bxf) {
  d: path("m9.5 21 2.5 -2.5 2.5 2.5");
}

:global(.v9il_wb-q) {
  d: path("M6 10h12");
}

</style>
