<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kafa4eb3l"/><path class="fbschg62a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevron-left-duotone-thin" {...props}></Icon>
<style>
:global(.fbschg62a) {
  d: path("m15 5 -7 7 7 7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kafa4eb3l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 5 -7 7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
