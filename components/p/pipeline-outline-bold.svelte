<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qvq8nib-l"/><path class="wg8_ddc1f"/><path class="zy1jzxj5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pipeline-outline-bold" {...props}></Icon>
<style>
:global(.qvq8nib-l) {
  d: path("M2 12a4 4 0 0 1 4 -4h12a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H6a4 4 0 0 1 -4 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wg8_ddc1f) {
  d: path("M6 12h6");
}

:global(.zy1jzxj5t) {
  d: path("M12.5 9.5 15 12l-2.5 2.5");
}

</style>
