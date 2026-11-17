<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ktnb3q9lf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cooking-pot" {...props}></Icon>
<style>
:global(.ktnb3q9lf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 11v7a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2v-7M5 11h14M3 14h2m14 0h2M6 11a6.5 6.5 0 0 1 12 0m-6-4V4m-2 0h4");
}

</style>
