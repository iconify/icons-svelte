<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aivjkkewm"/><path class="aobh7zpcx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cardboard-box-play" {...props}></Icon>
<style>
:global(.aivjkkewm) {
  d: path("M6.75 8h10.5A1.75 1.75 0 0 1 19 9.75v9a1.75 1.75 0 0 1-1.75 1.75H6.75A1.75 1.75 0 0 1 5 18.75v-9A1.75 1.75 0 0 1 6.75 8");
}

:global(.aobh7zpcx) {
  d: path("M9.5 20.5V14h5v6.5M5 8L2.5 3.5H7L9.5 8M19 8l2.5-4.5H17L14.5 8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
