<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhecbgbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:colour-complementary" {...props}></Icon>
<style>
:global(.uhecbgbbi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.25a9.5 9.5 0 0 1 6.5-6.5m12 12a9.5 9.5 0 0 1-6.5 6.5M12 2.5a9.5 9.5 0 0 1 9.5 9.5h-4A5.5 5.5 0 0 0 12 6.5Zm0 19A9.5 9.5 0 0 1 2.5 12h4a5.5 5.5 0 0 0 5.5 5.5Z");
}

</style>
