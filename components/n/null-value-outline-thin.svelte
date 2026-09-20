<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mp8d-bcnh"/><path class="l0kkv4bte"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:null-value-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l0kkv4bte) {
  d: path("M7 17 17 7");
}

:global(.mp8d-bcnh) {
  d: path("M5 12a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

</style>
