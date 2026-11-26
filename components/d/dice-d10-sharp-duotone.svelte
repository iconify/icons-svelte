<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="z8uuk02yn"/><path class="y0f-2fpvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dice-d10-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.y0f-2fpvn) {
  d: path("M12 2.0016L21.9984 12L12 21.9984L2.0016 12ZM8 12L12 2L16 12L12 16Z");
}

:global(.z8uuk02yn) {
  stroke-opacity: 0.4;
  d: path("M2 12L8 12M16 12L22 12M12 16L12 22");
}

</style>
