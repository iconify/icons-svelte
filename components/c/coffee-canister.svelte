<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zu-5ubhag"/><path class="fige7b_8m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coffee-canister" {...props}></Icon>
<style>
:global(.fige7b_8m) {
  d: path("M10.5 10.5h3a1.75 1.75 0 0 1 1.75 1.75v3.5a1.75 1.75 0 0 1-1.75 1.75h-3a1.75 1.75 0 0 1-1.75-1.75v-3.5a1.75 1.75 0 0 1 1.75-1.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zu-5ubhag) {
  d: path("M6.5 3h11a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2a2 2 0 0 1 2-2M6 7v12a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V7");
}

</style>
