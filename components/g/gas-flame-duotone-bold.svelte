<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b1flzybvf"/><path class="euu9p-b5e"/><path class="qik8460ao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gas-flame-duotone-bold" {...props}></Icon>
<style>
:global(.b1flzybvf) {
  fill: currentColor;
  d: path("M12 3c2 4 6 6 6 11a6 6 0 1 1 -12 0c0 -4 3 -5 3 -8 1 1 3 1 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.euu9p-b5e) {
  d: path("M12 3c2 4 6 6 6 11a6 6 0 1 1 -12 0c0 -4 3 -5 3 -8 1 1 3 1 3 -3");
}

:global(.qik8460ao) {
  d: path("M5 21h14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
