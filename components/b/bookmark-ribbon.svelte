<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_6jtg8fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bookmark-ribbon" {...props}></Icon>
<style>
:global(.j_6jtg8fp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 3h11.5a1.75 1.75 0 0 1 1.75 1.75v1a1.75 1.75 0 0 1-1.75 1.75H6.25A1.75 1.75 0 0 1 4.5 5.75v-1A1.75 1.75 0 0 1 6.25 3M8 7.5v14l4-3.5l4 3.5v-14");
}

</style>
