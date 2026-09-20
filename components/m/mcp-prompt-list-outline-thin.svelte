<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rcb0dgbps"/><path class="e0qzk-bpf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-prompt-list-outline-thin" {...props}></Icon>
<style>
:global(.e0qzk-bpf) {
  d: path("M19 10h-5l-4 4v6h10v-9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rcb0dgbps) {
  d: path("M16 4h-5L7 8v6h10V5");
}

</style>
