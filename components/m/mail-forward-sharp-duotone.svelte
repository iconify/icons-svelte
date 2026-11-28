<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j37vuubeg"/><path class="i9guoq2-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mail-forward-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.i9guoq2-a) {
  d: path("M18.7071 12.7071L22 16L18.7071 19.2929M22 16L15 16L15 21");
}

:global(.j37vuubeg) {
  stroke-opacity: 0.4;
  d: path("M12 20L2 20L2 4L22 4L22 10.7574M2 7L11.2929 11C11.7154 11.2817 12.2846 11.2817 12.7071 11L22 7");
}

</style>
