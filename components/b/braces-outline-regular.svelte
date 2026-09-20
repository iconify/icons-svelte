<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j-uhg7vsc"/><path class="m44kqpqtt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:braces-outline-regular" {...props}></Icon>
<style>
:global(.j-uhg7vsc) {
  d: path("M11 3H8v7l-2 2 2 2v7h3");
}

:global(.m44kqpqtt) {
  d: path("M13 3h3v7l2 2 -2 2v7h-3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
