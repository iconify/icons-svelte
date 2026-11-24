<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o2yt9o3rn"/><path class="a91ut1bon"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:courthouse-duocolor-sharp" {...props}></Icon>
<style>
:global(.a91ut1bon) {
  d: path("m12 3l9 4H3zM5 21v-4h14v4M3 21h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o2yt9o3rn) {
  stroke-opacity: 0.4;
  d: path("M7 7v10m5-10v10m5-10v10");
}

</style>
