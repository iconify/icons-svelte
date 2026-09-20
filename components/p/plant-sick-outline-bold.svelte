<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n-0bvdyee"/><path class="vt7vyubju"/><path class="e49gfxbmn"/><path class="ip9t47bii"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plant-sick-outline-bold" {...props}></Icon>
<style>
:global(.e49gfxbmn) {
  d: path("M12 10c-4 0 -7 2 -7 5 4 0 7 -2 7 -5");
}

:global(.ip9t47bii) {
  d: path("M12 8c4 0 7 2 7 5 -4 0 -7 -2 -7 -5");
}

:global(.n-0bvdyee) {
  d: path("M9 15v5h6v-5Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vt7vyubju) {
  d: path("M12 4v11");
}

</style>
