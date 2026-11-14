<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lxkdwt_9f"/><path class="wd8uzfbvo"/><path class="kajra0bem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:asparagus" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kajra0bem) {
  d: path("M10.25 5.5a1.75 3 0 1 0 3.5 0a1.75 3 0 1 0-3.5 0m-1.5 11h6.5");
}

:global(.lxkdwt_9f) {
  d: path("M12 8v12.5M6.5 9l4.25 11.75M17.5 9l-4.25 11.75m-3-15.25a1.75 3 0 1 0 3.5 0a1.75 3 0 1 0-3.5 0");
}

:global(.wd8uzfbvo) {
  d: path("M10.25 5.5a1.75 3 0 1 0 3.5 0a1.75 3 0 1 0-3.5 0");
}

</style>
