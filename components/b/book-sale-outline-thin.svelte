<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y4_6s7b5v"/><path class="wuvisubmw"/><path class="p-mto4usm"/><path class="aqrpc1aqy"/><path class="ktzvm-xej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:book-sale-outline-thin" {...props}></Icon>
<style>
:global(.aqrpc1aqy) {
  d: path("M12 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ktzvm-xej) {
  d: path("M17 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.p-mto4usm) {
  d: path("m12 15 7 -7");
}

:global(.wuvisubmw) {
  d: path("M8 3v18");
}

:global(.y4_6s7b5v) {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
