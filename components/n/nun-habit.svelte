<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qprhg8bdc"/><path class="flz7r_b9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:nun-habit" {...props}></Icon>
<style>
:global(.flz7r_b9k) {
  d: path("M12 7c2 0 3.5 1.75 3.5 4S14 15.25 12 15.25s-3.5-2-3.5-4.25S10 7 12 7M8.25 18.5q3.75-1.5 7.5 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qprhg8bdc) {
  d: path("M12 2.75c4.5 0 7.25 3.5 7.25 8v10.5H4.75v-10.5c0-4.5 2.75-8 7.25-8");
}

</style>
