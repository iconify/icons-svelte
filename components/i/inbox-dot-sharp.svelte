<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_a-2ikqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:inbox-dot-sharp" {...props}></Icon>
<style>
:global(.x_a-2ikqy) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21.6133 11.5228L22 12.1534L22 20L2 20L2 12.1534L7 4L15 4M2 13L8 13L10 16L14 16L16 13L22 13M22 6C22 7.1046 21.1046 8 20 8C18.8954 8 18 7.1046 18 6C18 4.8954 18.8954 4 20 4C21.1046 4 22 4.8954 22 6Z");
}

</style>
