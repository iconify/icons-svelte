<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dejb-0bmi"/><path class="x1xb02odd"/><path class="gkj6vbuly"/><path class="ui32hib9b"/><path class="iqxmkybol"/><path class="s_4-olb0v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:lesson-duotone-bold" {...props}></Icon>
<style>
:global(.dejb-0bmi) {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gkj6vbuly) {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.iqxmkybol) {
  d: path("M7 10a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.s_4-olb0v) {
  d: path("M12 7v3h3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ui32hib9b) {
  d: path("M5 20h14");
}

:global(.x1xb02odd) {
  fill: currentColor;
  d: path("M7 10a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
