<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ucfwazwsw"/><path class="a6ofj8tlq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pickaxe" {...props}></Icon>
<style>
:global(.a6ofj8tlq) {
  d: path("M12 6za1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5V7.5A1.5 1.5 0 0 1 12 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ucfwazwsw) {
  d: path("M3 8c4-4 14-4 18 0C17 6.5 7 6.5 3 8");
}

</style>
