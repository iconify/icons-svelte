<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhme2eb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:drop-alert" {...props}></Icon>
<style>
:global(.nhme2eb3y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5s7 7.5 7 12a7 7 0 0 1-14 0c0-4.5 7-12 7-12M12 9v5m0 3.25h.01");
}

</style>
