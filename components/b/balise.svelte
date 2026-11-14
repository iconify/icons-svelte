<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cnd7rabsw"/><path class="kl0lk4qlc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:balise" {...props}></Icon>
<style>
:global(.cnd7rabsw) {
  d: path("M5.5 15h13a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5h-13A2.5 2.5 0 0 1 3 17.5A2.5 2.5 0 0 1 5.5 15m4-3.5a3.5 3.5 0 0 1 5 0m-7-2a6.5 6.5 0 0 1 9 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kl0lk4qlc) {
  d: path("M5.25 7.25a9.5 9.5 0 0 1 13.5 0");
}

</style>
