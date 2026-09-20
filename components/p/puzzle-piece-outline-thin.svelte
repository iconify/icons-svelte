<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdh740b3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:puzzle-piece-outline-thin" {...props}></Icon>
<style>
:global(.hdh740b3e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4h6c0 -1.5 4 -1.5 4 0h6v6c1.5 0 1.5 4 0 4v6H4v-6c1.5 0 1.5 -4 0 -4Z");
}

</style>
