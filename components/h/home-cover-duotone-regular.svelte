<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="foemy1bum"/><path class="qtbc6tb3f"/><path class="uzpzz4brq"/><path class="nyw9-1r_v"/><path class="a3eibhdgt"/><path class="z26gfvqcs"/><path class="dqv6w4kbm"/><path class="jkw9k9b1p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-cover-duotone-regular" {...props}></Icon>
<style>
:global(.a3eibhdgt) {
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
}

:global(.dqv6w4kbm) {
  d: path("m8 16.5 4 -4 4 4");
}

:global(.foemy1bum) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkw9k9b1p) {
  d: path("M9 16.5V21h6v-4.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nyw9-1r_v) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 16.5V21h6v-4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qtbc6tb3f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4.5 9.5h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uzpzz4brq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 16.5 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z26gfvqcs) {
  d: path("M4.5 9.5h15");
}

</style>
