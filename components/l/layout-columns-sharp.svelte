<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a96l0dbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:layout-columns-sharp" {...props}></Icon>
<style>
:global(.a96l0dbrs) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 5L6 5L6 19L2 19ZM10 5L14 5L14 19L10 19ZM18 5L22 5L22 19L18 19Z");
}

</style>
