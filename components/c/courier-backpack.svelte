<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bnghffbam"/><path class="gmexwbb9r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:courier-backpack" {...props}></Icon>
<style>
:global(.bnghffbam) {
  d: path("M4.5 21.5V10a5 5 0 0 1 5-5h5a5 5 0 0 1 5 5v11.5ZM9.5 5V4A1.5 1.5 0 0 1 11 2.5h2A1.5 1.5 0 0 1 14.5 4v1");
}

:global(.gmexwbb9r) {
  d: path("M7.5 21.5v-7h9v7m-7-7v-4h5v4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
