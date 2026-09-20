<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eq8p65fcb"/><path class="r182r524c"/><path class="zf9agzw6m"/><path class="s7u5an2xj"/><path class="pf3d8ibrz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:high-score-outline-regular" {...props}></Icon>
<style>
:global(.eq8p65fcb) {
  d: path("M4 4v16h16V4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pf3d8ibrz) {
  d: path("m15 7 2 -2 2 2");
}

:global(.r182r524c) {
  d: path("M7 9h10");
}

:global(.s7u5an2xj) {
  d: path("M7 17h8");
}

:global(.zf9agzw6m) {
  d: path("M7 13h7");
}

</style>
