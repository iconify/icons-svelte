<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xdcgmbvng"/><path class="kcg4zobos"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-checks-duotone" {...props}></Icon>
<style>
:global(.kcg4zobos) {
  d: path("M2 7L4 9L8 5M2 17L4 19L8 15");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xdcgmbvng) {
  stroke-opacity: 0.4;
  d: path("M12 7L22 7M12 17L22 17");
}

</style>
