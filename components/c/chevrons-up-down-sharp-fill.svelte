<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivzo09bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevrons-up-down-sharp-fill" {...props}></Icon>
<style>
:global(.ivzo09bad) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.7071 9.2929L12 4L17.2929 9.2929M6.7071 14.7071L12 20L17.2929 14.7071");
}

</style>
