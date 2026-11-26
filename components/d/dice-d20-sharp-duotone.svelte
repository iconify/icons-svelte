<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ghn_62oze"/><path class="vkqvp1btw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dice-d20-sharp-duotone" {...props}></Icon>
<style>
:global(.ghn_62oze) {
  stroke-opacity: 0.4;
  d: path("M3.3978 7.0154L12 7L20.6022 7.0154M3.3978 7.0154L8 14L12 22L16 14L20.6022 7.0154");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vkqvp1btw) {
  d: path("M12 2.0023L21 6.7872L21 17.2128L12 21.9977L3 17.2128L3 6.7872ZM12 7L8 14L16 14Z");
}

</style>
