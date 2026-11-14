<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzdfi0bpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:empty-set" {...props}></Icon>
<style>
:global(.gzdfi0bpa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0M7 20.5l10-17");
}

</style>
