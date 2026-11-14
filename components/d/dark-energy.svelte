<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6xdnubqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dark-energy" {...props}></Icon>
<style>
:global(.w6xdnubqv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0m7-4l4-4m-4 0h4v4M8 8L4 4m4 0H4v4m12 8l4 4m-4 0h4v-4M8 16l-4 4m4 0H4v-4");
}

</style>
