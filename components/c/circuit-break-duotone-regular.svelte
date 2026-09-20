<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cj3m7pz3h"/><path class="yoyo2jwwv"/><path class="zqn6cu9ju"/><path class="v5td4_4qf"/><path class="km504hb-m"/><path class="w7wsu271f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:circuit-break-duotone-regular" {...props}></Icon>
<style>
:global(.cj3m7pz3h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 16h6.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.km504hb-m) {
  d: path("M15.5 16H22");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v5td4_4qf) {
  d: path("M2 16h6.5");
}

:global(.w7wsu271f) {
  d: path("m8.5 16 8 -8");
}

:global(.yoyo2jwwv) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15.5 16H22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zqn6cu9ju) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8.5 16 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
