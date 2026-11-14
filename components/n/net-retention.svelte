<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fjmk1tc6j"/><path class="bd-w_8bqd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:net-retention" {...props}></Icon>
<style>
:global(.bd-w_8bqd) {
  d: path("m2 14l2-2l2 2m2.5-2a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

:global(.fjmk1tc6j) {
  d: path("M12 4a8 8 0 1 1-8 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
