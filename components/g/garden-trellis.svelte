<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eefusqedz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:garden-trellis" {...props}></Icon>
<style>
:global(.eefusqedz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 21.5V3h14v18.5M5 17h14M5 7l10 10M9 3l10 10M5 13L15 3M9 17L19 7");
}

</style>
