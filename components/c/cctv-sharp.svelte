<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5ijkbl6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cctv-sharp" {...props}></Icon>
<style>
:global(.v5ijkbl6c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18v4H3Zm2 4v7a7 7 0 0 0 14 0V7M9 14a3 3 0 1 0 6 0a3 3 0 0 0-6 0m3 0h.01");
}

</style>
