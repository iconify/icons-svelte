<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f4vji8emu"/><path class="i3xzrim4g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:outdent-duocolor" {...props}></Icon>
<style>
:global(.f4vji8emu) {
  stroke-opacity: 0.4;
  d: path("m8 8l-4 4l4 4");
}

:global(.i3xzrim4g) {
  d: path("M12 6h8m-8 4h8m-8 4h8m-8 4h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
