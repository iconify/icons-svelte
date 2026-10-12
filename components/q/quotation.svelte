<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="it-qfxbvy"/><path class="w5tntwbxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:quotation" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.it-qfxbvy) {
  d: path("M11.75 21.25h-4.5a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5h6.5l5.5 5.5v3.5");
}

:global(.w5tntwbxd) {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-11 .5h2.5m-2.5 3.5h4m3 2.25h2q.75 0 1.28.53l1.94 1.94q.53.53 0 1.06l-2.44 2.44q-.53.53-1.06 0l-1.94-1.94q-.53-.53-.53-1.28v-2q0-.75.75-.75");
}

</style>
