<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ucbzzjbat"/><path class="t3_tm1wcl"/><path class="mckspnbyn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:highlighter-outline-regular" {...props}></Icon>
<style>
:global(.mckspnbyn) {
  d: path("M3 17h9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.t3_tm1wcl) {
  d: path("m14 8 4 -4");
}

:global(.ucbzzjbat) {
  d: path("m11 11 3 -3 2 2 -3 3Z");
}

</style>
