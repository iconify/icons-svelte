<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjkfyrbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:metal-sample" {...props}></Icon>
<style>
:global(.jjkfyrbar) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5L6 12l2.5-5.5h7L18 12l3.5 5.5ZM6 12h12");
}

</style>
