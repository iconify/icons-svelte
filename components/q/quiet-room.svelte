<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ob4r4xn_l"/><path class="wcppgw61r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:quiet-room" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ob4r4xn_l) {
  d: path("M4.75 21.25V4.75a2 2 0 0 1 2-2h10.5a2 2 0 0 1 2 2v16.5m-16.5 0h18.5");
}

:global(.wcppgw61r) {
  d: path("M13.5 7.5a4 4 0 1 0 2.75 6.25A5 5 0 0 1 13.5 7.5");
}

</style>
