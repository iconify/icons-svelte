<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nnzlfsekh"/><path class="teszqoqtj"/><path class="zqsgc7abe"/><path class="g31q_jb0h"/><path class="mxzk029nb"/><path class="zrsj1cc7l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:amortised-cost-outline-regular" {...props}></Icon>
<style>
:global(.g31q_jb0h) {
  d: path("M9 10v4");
}

:global(.mxzk029nb) {
  d: path("M12 10v4");
}

:global(.nnzlfsekh) {
  d: path("M2 8a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.teszqoqtj) {
  d: path("M5.5 10.5v3");
}

:global(.zqsgc7abe) {
  d: path("M18.5 10.5v3");
}

:global(.zrsj1cc7l) {
  d: path("M15 10v4");
}

</style>
