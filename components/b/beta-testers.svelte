<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnxi6xzkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:beta-testers" {...props}></Icon>
<style>
:global(.rnxi6xzkl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 8.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M6.5 21c0-3.5 2.5-5.5 5.5-5.5s5.5 2 5.5 5.5M2.5 7a2 2 0 1 0 4 0a2 2 0 1 0-4 0m15 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-15 11v-1.5c0-2.75 1.5-4.5 4-4.5m15 6v-1.5c0-2.75-1.5-4.5-4-4.5");
}

</style>
