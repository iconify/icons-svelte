<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s91-42bkk"/><path class="ef5ubjb0b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:interrupt-duotone-thin" {...props}></Icon>
<style>
:global(.ef5ubjb0b) {
  d: path("M18 2 8 12h5l-8 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s91-42bkk) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 2 8 12h5l-8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
