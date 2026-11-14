<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwult4bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:person-dress" {...props}></Icon>
<style>
:global(.zwult4bab) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M11.287 8h1.426a1.75 1.75 0 0 1 1.671 1.228l1.406 4.5A1.75 1.75 0 0 1 14.12 16H9.88a1.75 1.75 0 0 1-1.67-2.272l1.406-4.5A1.75 1.75 0 0 1 11.287 8m-.787 8v5m3-5v5");
}

</style>
