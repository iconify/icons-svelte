<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ee3z7kb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:remaining-distance" {...props}></Icon>
<style>
:global(.ee3z7kb5a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 21.5l7-19m12 19l-7-19M12 20V9m-2.5 2.5L12 9l2.5 2.5");
}

</style>
