<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkz3zacic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clipboard-type-sharp" {...props}></Icon>
<style>
:global(.wkz3zacic) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 4L4 4L4 22L20 22L20 4L17 4M7 2L17 2L17 7L7 7L7 2ZM8 15L8 12L16 12L16 15M12 12L12 18M9 18L15 18");
}

</style>
