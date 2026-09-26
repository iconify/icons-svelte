<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gijl0dblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:inbox-sharp" {...props}></Icon>
<style>
:global(.gijl0dblz) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 4L17 4L22 12.1534L22 20L2 20L2 12.1534L7 4ZM2 13L8 13L10 16L14 16L16 13L22 13");
}

</style>
