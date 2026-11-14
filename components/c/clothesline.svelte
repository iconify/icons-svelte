<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1u531x9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:clothesline" {...props}></Icon>
<style>
:global(.r1u531x9x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5V21m17-17.5V21M3.5 6h17M9 6L6.5 8.5l2 2l1-.75V17h5V9.75l1 .75l2-2L15 6");
}

</style>
