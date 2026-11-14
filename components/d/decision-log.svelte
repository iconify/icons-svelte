<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gli7hhbby"/><path class="ju5kit9ai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:decision-log" {...props}></Icon>
<style>
:global(.gli7hhbby) {
  d: path("M12 20.5V11L5 4m7 7l7-7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ju5kit9ai) {
  d: path("M5 9V4h5m4 0h5v5");
}

</style>
