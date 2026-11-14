<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n7w0nj00v"/><path class="mgm6lvbwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arrow-turn-up-right" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mgm6lvbwx) {
  d: path("m12.5 9l4-4l4 4");
}

:global(.n7w0nj00v) {
  d: path("M3.5 19h8a5 5 0 0 0 5-5V5");
}

</style>
