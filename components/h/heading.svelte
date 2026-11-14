<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc1k9jb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:heading" {...props}></Icon>
<style>
:global(.bc1k9jb9s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 4v16M19 4v16M5 12h14");
}

</style>
