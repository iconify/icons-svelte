<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geavyv7wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:egg-drop" {...props}></Icon>
<style>
:global(.geavyv7wk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9.5a8 6.5 0 0 1 16 0a2 2 0 0 0-4 0a2 2 0 0 0-4 0a2 2 0 0 0-4 0a2 2 0 0 0-4 0m4.5 7.75a3.5 4 0 1 0 7 0a3.5 4 0 1 0-7 0M8 9.5l4 3.75m4-3.75l-4 3.75");
}

</style>
