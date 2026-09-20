<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rugctacrb"/><path class="e1cd9tzjc"/><path class="l0gojqv3g"/><path class="qdn88l2uv"/><path class="g4h6r4ykz"/><path class="pkaragbav"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:arrow-down-to-line-duotone-thin" {...props}></Icon>
<style>
:global(.e1cd9tzjc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 4v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g4h6r4ykz) {
  d: path("M12 4v12");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l0gojqv3g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 12 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pkaragbav) {
  d: path("m8 12 4 4 4 -4");
}

:global(.qdn88l2uv) {
  d: path("M7 20h10");
}

:global(.rugctacrb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 20h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
