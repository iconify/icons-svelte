<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j4pe68_by"/><path class="rl0hurbau"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:check-badge" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j4pe68_by) {
  d: path("m20.712 13.05l-1.188 1.584a1.75 1.75 0 0 0-.334.819l-.263 1.971a1.75 1.75 0 0 1-1.503 1.503l-1.971.263a1.75 1.75 0 0 0-.819.334l-1.584 1.188a1.75 1.75 0 0 1-2.1 0l-1.584-1.188a1.75 1.75 0 0 0-.819-.334l-1.971-.263a1.75 1.75 0 0 1-1.503-1.503l-.263-1.971a1.75 1.75 0 0 0-.334-.819L3.287 13.05a1.75 1.75 0 0 1 0-2.1l1.189-1.584a1.75 1.75 0 0 0 .334-.819l.263-1.971a1.75 1.75 0 0 1 1.503-1.503l1.971-.263a1.75 1.75 0 0 0 .819-.334l1.584-1.189a1.75 1.75 0 0 1 2.1 0l1.584 1.189a1.75 1.75 0 0 0 .819.334l1.971.263a1.75 1.75 0 0 1 1.503 1.503l.263 1.971a1.75 1.75 0 0 0 .334.819l1.188 1.584a1.75 1.75 0 0 1 0 2.1");
}

:global(.rl0hurbau) {
  d: path("m8.5 12l2.5 2.5l4.5-5");
}

</style>
