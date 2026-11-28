<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xavmyvb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:redirect" {...props}></Icon>
<style>
:global(.xavmyvb9s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 4L22 10L16 16M22 10H12C10.8954 10 10 10.8954 10 12V18C10 19.1046 9.1046 20 8 20H2");
}

</style>
