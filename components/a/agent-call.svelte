<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="by9a4e0yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:agent-call" {...props}></Icon>
<style>
:global(.by9a4e0yo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.072 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.704 0 1.368.081M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m9 7.5h5a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H18L16 21v-1.5h-.5a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1");
}

</style>
