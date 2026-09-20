<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="caznxbcdb"/><path class="ag27qibsz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevrons-up-down-outline-regular" {...props}></Icon>
<style>
:global(.ag27qibsz) {
  d: path("m7 15 5 5 5 -5");
}

:global(.caznxbcdb) {
  d: path("m7 9 5 -5 5 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
