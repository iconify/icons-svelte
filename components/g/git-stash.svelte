<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7yre729t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-stash" {...props}></Icon>
<style>
:global(.g7yre729t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-7 8v5a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-5m-9-6v7m-3-3l3 3l3-3");
}

</style>
