<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6pjrd3vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:paragraph" {...props}></Icon>
<style>
:global(.o6pjrd3vr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4.5h12m-17 5h17m-17 5h17m-17 5H13");
}

</style>
