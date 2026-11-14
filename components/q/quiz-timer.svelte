<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6t82pb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:quiz-timer" {...props}></Icon>
<style>
:global(.t6t82pb1c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 13.5a7.75 7.75 0 1 0 15.5 0a7.75 7.75 0 1 0-15.5 0M10 2.5h4m-2 11v-4m0 4l3 1.5M12 2.5v3.25");
}

</style>
