<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi49tccmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:audio-article-play" {...props}></Icon>
<style>
:global(.pi49tccmc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5v5M7.5 5v14M12 2.5v19M16.5 5v7M21 8v3.5M16 15l5.5 3.25L16 21.5Z");
}

</style>
