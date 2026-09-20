<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aaakc7r5n"/><path class="cssae_b2t"/><path class="l4e9mib8f"/><path class="n-0bvdyee"/><path class="vt7vyubju"/><path class="e49gfxbmn"/><path class="ip9t47bii"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plant-sick-duotone-regular" {...props}></Icon>
<style>
:global(.aaakc7r5n) {
  fill: currentColor;
  d: path("M9 15v5h6v-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.cssae_b2t) {
  fill: currentColor;
  d: path("M12 10c-4 0 -7 2 -7 5 4 0 7 -2 7 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.e49gfxbmn) {
  d: path("M12 10c-4 0 -7 2 -7 5 4 0 7 -2 7 -5");
}

:global(.ip9t47bii) {
  d: path("M12 8c4 0 7 2 7 5 -4 0 -7 -2 -7 -5");
}

:global(.l4e9mib8f) {
  fill: currentColor;
  d: path("M12 8c4 0 7 2 7 5 -4 0 -7 -2 -7 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n-0bvdyee) {
  d: path("M9 15v5h6v-5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vt7vyubju) {
  d: path("M12 4v11");
}

</style>
