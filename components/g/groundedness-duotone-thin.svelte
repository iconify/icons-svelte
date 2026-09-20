<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f4kv94yfp"/><path class="cf-dqybgk"/><path class="duxy6wbvl"/><path class="ok9ioqb8x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:groundedness-duotone-thin" {...props}></Icon>
<style>
:global(.cf-dqybgk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.duxy6wbvl) {
  d: path("m7 9 4 4 6 -6");
}

:global(.f4kv94yfp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 9 4 4 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ok9ioqb8x) {
  d: path("M4 17h16");
}

</style>
