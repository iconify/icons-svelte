<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpb8zfl-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:club-suit" {...props}></Icon>
<style>
:global(.gpb8zfl-l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 15.75L9.5 20.5h5L13 15.75a4 4 0 1 0 1.75-5.5a4 4 0 1 0-5.5 0a4 4 0 1 0 1.75 5.5");
}

</style>
