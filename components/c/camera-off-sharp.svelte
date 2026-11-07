<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz406vhsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:camera-off-sharp" {...props}></Icon>
<style>
:global(.oz406vhsd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 20H3V7h3m4-3zh4l3 3h4v9M9.879 10.879a3 3 0 0 0 4.243 4.243M2 3l19 19");
}

</style>
