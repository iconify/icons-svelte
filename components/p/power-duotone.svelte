<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to0c2ub7t"><path class="dnjmyosxc"/><path class="kcrtoqb_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:power-duotone" {...props}></Icon>
<style>
:global(.dnjmyosxc) {
  stroke-opacity: 0.4;
  d: path("M18.82 4.6865C20.8483 6.5779 22 9.2267 22 12C22 17.5228 17.5228 22 12 22C6.4772 22 2 17.5228 2 12C2 9.2267 3.1517 6.5779 5.18 4.6865");
}

:global(.kcrtoqb_y) {
  d: path("M12 2L12 9.7563");
}

:global(.to0c2ub7t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
