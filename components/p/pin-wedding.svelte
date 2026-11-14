<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sk5kzbc8q"/><path class="l603-lbtx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-wedding" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l603-lbtx) {
  d: path("M20.322 14.77a6 6 0 1 1 .536-4.069M13.5 3.625l.05-.062A1.5 1.5 0 0 1 14.721 3h.558a1.5 1.5 0 0 1 1.171.563l.05.062a.836.836 0 0 1-.102 1.152l-.41.359a1.5 1.5 0 0 1-1.976 0l-.41-.359a.836.836 0 0 1-.102-1.152");
}

:global(.sk5kzbc8q) {
  d: path("M3.678 12.23a6 6 0 1 1-.536 4.069");
}

</style>
