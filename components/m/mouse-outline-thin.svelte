<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nptt5bbgx"/><path class="r182r524c"/><path class="uokpg3btu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mouse-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nptt5bbgx) {
  d: path("M7 7a5 5 0 0 1 5 -5 5 5 0 0 1 5 5v10a5 5 0 0 1 -5 5 5 5 0 0 1 -5 -5Z");
}

:global(.r182r524c) {
  d: path("M7 9h10");
}

:global(.uokpg3btu) {
  d: path("M12 5v3");
}

</style>
