<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i2-ny_bzf"/><path class="g7akhoeoj"/><path class="jyg-5ub3c"/><path class="wtnr1t2-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bird-feeder-outline-regular" {...props}></Icon>
<style>
:global(.g7akhoeoj) {
  d: path("m6 13 6 -6 6 6");
}

:global(.i2-ny_bzf) {
  d: path("M12 3v4");
}

:global(.jyg-5ub3c) {
  d: path("M8 13v5h8v-5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wtnr1t2-w) {
  d: path("M9 21h6");
}

</style>
