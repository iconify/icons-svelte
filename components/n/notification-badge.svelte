<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j7zdxsb9u"/><path class="s6u2_13io"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:notification-badge" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j7zdxsb9u) {
  d: path("M12.5 3.5H7A3.5 3.5 0 0 0 3.5 7v10A3.5 3.5 0 0 0 7 20.5h10a3.5 3.5 0 0 0 3.5-3.5v-6");
}

:global(.s6u2_13io) {
  d: path("M18 3h1a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 19 8h-1a2.5 2.5 0 0 1-2.5-2.5A2.5 2.5 0 0 1 18 3");
}

</style>
