<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yycnewbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:freedom-of-speech" {...props}></Icon>
<style>
:global(.yycnewbqn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3.75h10a2 2 0 0 1 2 2v7.5a2 2 0 0 1-2 2H10l-4 3.5v-3.5H4.75a2 2 0 0 1-2-2v-7.5a2 2 0 0 1 2-2M6.5 8H13m-6.5 3h4M19 6.25c1.5 2 1.5 4.5 0 6.5");
}

</style>
