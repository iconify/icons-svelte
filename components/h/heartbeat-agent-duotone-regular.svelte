<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kosxb-loy"/><path class="galwllb4y"/><path class="skbifdbcx"/><path class="a-m7xvbdg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:heartbeat-agent-duotone-regular" {...props}></Icon>
<style>
:global(.a-m7xvbdg) {
  d: path("M10 18h3l2.5 -2.5L18 18h3");
}

:global(.galwllb4y) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M10 18h3l2.5 -2.5L18 18h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kosxb-loy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.skbifdbcx) {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>
