<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b4kmbcifq"/><path class="bsyq0zp1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-close-duocolor-sharp" {...props}></Icon>
<style>
:global(.b4kmbcifq) {
  stroke-opacity: 0.4;
  d: path("m16 4l4 4m0-4l-4 4");
}

:global(.bsyq0zp1v) {
  d: path("M21 13v6H3V5h8M3 5l6 6h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
