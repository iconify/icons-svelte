<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rjrs_5bsc"/><path class="xslfg2evh"/><path class="b266jkbmh"/><path class="m-436sbse"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:countdown-sale-outline-regular" {...props}></Icon>
<style>
:global(.b266jkbmh) {
  d: path("M7 3v4l5 5 5 -5V3");
}

:global(.m-436sbse) {
  d: path("M7 21v-4l5 -5 5 5v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rjrs_5bsc) {
  d: path("M6 3h12");
}

:global(.xslfg2evh) {
  d: path("M6 21h12");
}

</style>
