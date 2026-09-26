<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtibcdcok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-check-sharp" {...props}></Icon>
<style>
:global(.wtibcdcok) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 20L3 20L3 4L9.5 4L12 6.5L21 6.5L21 11M14.7071 16.7071L17 19L21.2929 14.7071");
}

</style>
