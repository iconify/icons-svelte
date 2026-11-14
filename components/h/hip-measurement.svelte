<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uqk735lfa"/><path class="rb-nnp8lw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hip-measurement" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rb-nnp8lw) {
  d: path("M9.125 6.625za1.237 1.237 0 0 0 0 1.75a.513.513 0 0 0 .875-.362V6.987a.513.513 0 0 0-.875-.362m5.75 0za1.237 1.237 0 0 1 0 1.75a.513.513 0 0 1-.875-.362V6.987a.513.513 0 0 1 .875-.362");
}

:global(.uqk735lfa) {
  d: path("M5 2.5h14l1.5 19h-6L12 11L9.5 21.5h-6Zm3.25 5h7.5");
}

</style>
