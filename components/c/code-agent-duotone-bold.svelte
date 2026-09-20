<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uovt8_2nx"/><path class="omwvqac0a"/><path class="nfjg54brz"/><path class="pl_bf8bxp"/><path class="rdh7npbwk"/><path class="cr7psearj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:code-agent-duotone-bold" {...props}></Icon>
<style>
:global(.cr7psearj) {
  d: path("m15 13 2.5 2.5L15 18");
}

:global(.nfjg54brz) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 13 2.5 2.5L15 18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.omwvqac0a) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 13 -2.5 2.5L9 18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pl_bf8bxp) {
  d: path("M13.69 2.87a4 4 0 1 1 -3.38 0");
}

:global(.rdh7npbwk) {
  d: path("m9 13 -2.5 2.5L9 18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uovt8_2nx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.69 2.87a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
