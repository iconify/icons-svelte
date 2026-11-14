<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ck6lwowvk"/><path class="bn487jb_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pin-sauna" {...props}></Icon>
<style>
:global(.bn487jb_c) {
  d: path("M9.5 13C8 11.25 11 9.5 9.5 6.75m5 6.25c-1.5-1.75 1.5-3.5 0-6.25M8 15.5h8");
}

:global(.ck6lwowvk) {
  d: path("M12 21.5C9 19 3.5 15 3.5 11a8.5 8.5 0 0 1 17 0c0 4-5.5 8-8.5 10.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
