<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cnjkjfbvs"/><path class="po0gsxbro"/><path class="x5uilr-gd"/><path class="j3tm7xb5y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:game-over-outline-regular" {...props}></Icon>
<style>
:global(.cnjkjfbvs) {
  d: path("M3 5v14h18V5Z");
}

:global(.j3tm7xb5y) {
  d: path("M14 15h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.po0gsxbro) {
  d: path("m8 10 4 4");
}

:global(.x5uilr-gd) {
  d: path("m12 10 -4 4");
}

</style>
