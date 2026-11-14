<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fk5er_b-q"/><path class="lcvcuy-hk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:coding-toy" {...props}></Icon>
<style>
:global(.fk5er_b-q) {
  d: path("M8.5 6.5h7A3.5 3.5 0 0 1 19 10v3.5a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 13.5V10a3.5 3.5 0 0 1 3.5-3.5M12 3v3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lcvcuy-hk) {
  d: path("M6.5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-4-7.5h.01m4.99 0h.01");
}

</style>
