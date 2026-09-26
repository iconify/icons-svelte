<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6a78ihov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:book-plus-sharp" {...props}></Icon>
<style>
:global(.e6a78ihov) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 13L20 2L4 2L4 22M11 22L4 22L4 18L11 18M8 6L8 14M17 15L17 23M13 19L21 19");
}

</style>
