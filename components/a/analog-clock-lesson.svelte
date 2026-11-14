<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njc9r9bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:analog-clock-lesson" {...props}></Icon>
<style>
:global(.njc9r9bwh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0m9.5 0V6.5m0 5.5l4 2.25M12 12h.01");
}

</style>
