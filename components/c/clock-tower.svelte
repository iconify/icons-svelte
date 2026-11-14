<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bwayy8peh"/><path class="zsx9s7svv"/><path class="jmy4pabyw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:clock-tower" {...props}></Icon>
<style>
:global(.bwayy8peh) {
  d: path("M8 21.5V9l4-4.5L16 9v12.5m-4-19v2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jmy4pabyw) {
  d: path("M12 11v1.5h1.25M6 21.5h12");
}

:global(.zsx9s7svv) {
  d: path("M9.25 12.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0");
}

</style>
