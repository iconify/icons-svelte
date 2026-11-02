<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b51oo275q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:crown" {...props}></Icon>
<style>
:global(.b51oo275q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 4l4 6l5-4l-1.701 9.358A2 2 0 0 1 17.33 17H6.669a2 2 0 0 1-1.968-1.642L3 6l5 4zM5 21h14");
}

</style>
