<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftrgz3bam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dancing" {...props}></Icon>
<style>
:global(.ftrgz3bam) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M19 5l-7 4.5L5.5 12M12 9.5L11 15l-2.5 6.5M11 15l5.5 1l-1 5");
}

</style>
