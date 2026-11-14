<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vje1dub9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:kaizen" {...props}></Icon>
<style>
:global(.vje1dub9l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5h4.5V16H12v-4.5h4.5V7H21M4 12.5L10.5 6m-4 0h4v4");
}

</style>
