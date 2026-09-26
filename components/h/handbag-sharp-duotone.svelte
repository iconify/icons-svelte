<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjdnx9y7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:handbag-sharp-duotone" {...props}></Icon>
<style>
:global(.mjdnx9y7v) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 7C8 4.7909 9.7909 3 12 3C14.2091 3 16 4.7909 16 7M4 7L20 7L20 21L4 21L4 7Z");
}

</style>
