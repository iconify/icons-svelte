<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ortw0s1jo"/><path class="z55i2tbmp"/><path class="rt75x1b6c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:focus-session-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ortw0s1jo) {
  d: path("M5 14a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

:global(.rt75x1b6c) {
  d: path("M12 7V4");
}

:global(.z55i2tbmp) {
  d: path("m9 4 3 3 3 -3");
}

</style>
