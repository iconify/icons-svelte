<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yx_0bvsxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crackers" {...props}></Icon>
<style>
:global(.yx_0bvsxt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5a3.5 3.5 0 0 1 5 0a3.5 3.5 0 0 1 5 0a3.5 3.5 0 0 1 5 0a3.5 3.5 0 0 1 0 5a3.5 3.5 0 0 1 0 5a3.5 3.5 0 0 1 0 5a3.5 3.5 0 0 1-5 0a3.5 3.5 0 0 1-5 0a3.5 3.5 0 0 1-5 0a3.5 3.5 0 0 1 0-5a3.5 3.5 0 0 1 0-5a3.5 3.5 0 0 1 0-5M9 9h.01M15 9h.01M9 15h.01M15 15h.01");
}

</style>
