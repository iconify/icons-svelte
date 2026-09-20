<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mp8d-bcnh"/><path class="l0kkv4bte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:null-value-outline-regular" {...props}></Icon>
<style>
:global(.l0kkv4bte) {
  d: path("M7 17 17 7");
}

:global(.mp8d-bcnh) {
  d: path("M5 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
