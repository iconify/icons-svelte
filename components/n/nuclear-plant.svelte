<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zo0gq0buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:nuclear-plant" {...props}></Icon>
<style>
:global(.zo0gq0buw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21q4-6.5 2.5-13h8q-1.5 6.5 2.5 13Zm4-16A2 2 0 0 1 13 3.5a2 2 0 0 1 3.5 1");
}

</style>
