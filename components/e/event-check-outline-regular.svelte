<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v-jogvb5z"/><path class="l9-vpjbes"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-check-outline-regular" {...props}></Icon>
<style>
:global(.l9-vpjbes) {
  d: path("m13 14 2.5 2.5L20 12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v-jogvb5z) {
  d: path("m10 6 -5 5h4l-5 5");
}

</style>
