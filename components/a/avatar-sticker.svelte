<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nkfxw4bjg"/><path class="qvdu02blm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:avatar-sticker" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nkfxw4bjg) {
  d: path("M5.5 3h11L21 7.5v11a2.5 2.5 0 0 1-2.5 2.5h-13A2.5 2.5 0 0 1 3 18.5v-13A2.5 2.5 0 0 1 5.5 3");
}

:global(.qvdu02blm) {
  d: path("M16.5 3v2.5a2 2 0 0 0 2 2H21M8.5 10a3 3 0 1 0 6 0a3 3 0 1 0-6 0M6 21c0-3.25 2.5-5 5.5-5s5.5 1.75 5.5 5");
}

</style>
