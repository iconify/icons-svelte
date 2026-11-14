<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yppf7pf7d"/><path class="pb4-_3bdw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:gadget-watch-cover" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pb4-_3bdw) {
  d: path("M12 9.5V12l1.5 1");
}

:global(.yppf7pf7d) {
  d: path("M12 6.5za5 5 0 0 1 5 5v1a5 5 0 0 1-5 5a5 5 0 0 1-5-5v-1a5 5 0 0 1 5-5m-3 0l.75-4h4.5l.75 4m-6 11l.75 4h4.5l.75-4");
}

</style>
