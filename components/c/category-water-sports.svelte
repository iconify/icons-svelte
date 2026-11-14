<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjdbkf4_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-water-sports" {...props}></Icon>
<style>
:global(.qjdbkf4_l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13C5 10 7 10 9 12q3 3 6 0c2-2 4-2 6.5 1m-19 5C5 15 7 15 9 17q3 3 6 0c2-2 4-2 6.5 1M12 4v5");
}

</style>
