<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2itfyboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:diagram-subtask-sharp" {...props}></Icon>
<style>
:global(.p2itfyboc) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3L14 3L14 8L3 8L3 3ZM10 16L21 16L21 21L10 21L10 16ZM6 8L6 18.5L10 18.5");
}

</style>
