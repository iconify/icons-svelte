<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mu5pjkbqo"/><path class="spi9wczkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:game-board-outline-regular" {...props}></Icon>
<style>
:global(.mu5pjkbqo) {
  d: path("M3 3v18h18V3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.spi9wczkf) {
  d: path("M8 8v8h8V8Z");
}

</style>
