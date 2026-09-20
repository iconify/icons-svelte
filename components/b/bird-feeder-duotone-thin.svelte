<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="en1fcactg"/><path class="p8buz1t1r"/><path class="hsx22rmke"/><path class="you115stq"/><path class="i2-ny_bzf"/><path class="g7akhoeoj"/><path class="jyg-5ub3c"/><path class="wtnr1t2-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bird-feeder-duotone-thin" {...props}></Icon>
<style>
:global(.en1fcactg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g7akhoeoj) {
  d: path("m6 13 6 -6 6 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hsx22rmke) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 13v5h8v-5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.i2-ny_bzf) {
  d: path("M12 3v4");
}

:global(.jyg-5ub3c) {
  d: path("M8 13v5h8v-5");
}

:global(.p8buz1t1r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 13 6 -6 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wtnr1t2-w) {
  d: path("M9 21h6");
}

:global(.you115stq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 21h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
