<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o8wr52b0x"/><path class="c3-l2nbwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:audio-lines-mid-two-tone" {...props}></Icon>
<style>
:global(.c3-l2nbwu) {
  d: path("M4 10.5V13.5M12 5V19M20 10.5V13.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o8wr52b0x) {
  stroke-opacity: 0.4;
  d: path("M8 8V16M16 10V14");
}

</style>
