<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yrm0q7bju"/><path class="d8z1r1beo"/><path class="wzx0dxb2r"/><path class="g31q_jb0h"/><path class="mxzk029nb"/><path class="zrsj1cc7l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:retry-policy-duotone-regular" {...props}></Icon>
<style>
:global(.d8z1r1beo) {
  d: path("M15 5h3a3 3 0 0 1 3 3v9a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

:global(.g31q_jb0h) {
  d: path("M9 10v4");
}

:global(.mxzk029nb) {
  d: path("M12 10v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wzx0dxb2r) {
  d: path("m12 2 3 3 -3 3");
}

:global(.yrm0q7bju) {
  fill: currentColor;
  d: path("M15 5h3a3 3 0 0 1 3 3v9a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.zrsj1cc7l) {
  d: path("M15 10v4");
}

</style>
