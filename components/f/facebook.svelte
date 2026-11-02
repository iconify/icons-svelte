<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwbo4nbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:facebook" {...props}></Icon>
<style>
:global(.zwbo4nbbf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 14h3l1-4h-4m-4 0H7v4h3m0 0v7h4v-7m0-4V8a1 1 0 0 1 1-1h3V3h-3a5 5 0 0 0-5 5v2");
}

</style>
