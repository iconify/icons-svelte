<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8cq202lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-minus-corner-sharp" {...props}></Icon>
<style>
:global(.o8cq202lt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 19H3V5h18v6M3 5l6 6h6l6-6m-6 12h6");
}

</style>
