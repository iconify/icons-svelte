<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y7uqdfbgj"/><path class="my8ijhbaa"/><path class="aw36cedja"/><path class="w7sxxlcqv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:permission-grant-outline-thin" {...props}></Icon>
<style>
:global(.aw36cedja) {
  d: path("M16 15h5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.my8ijhbaa) {
  d: path("M4 10a4 4 0 0 1 8 0");
}

:global(.w7sxxlcqv) {
  d: path("m18 12 3 3 -3 3");
}

:global(.y7uqdfbgj) {
  d: path("M2 12a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
