<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j7qjn6psg"/><path class="n1xtjfrkh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:moon-waxing" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j7qjn6psg) {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 1 0-18 0");
}

:global(.n1xtjfrkh) {
  fill: currentColor;
  d: path("M12 3a9 9 0 0 1 0 18a4.5 9 0 0 1 0-18");
}

</style>
