<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku0e1mbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:parking-lights" {...props}></Icon>
<style>
:global(.ku0e1mbvi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 8.5h.25a3.5 3.5 0 0 1 0 7h-.25Zm-2.5 0h-.25a3.5 3.5 0 0 0 0 7h.25ZM19 12h2.25m-2.5-3.25l2-1.25m-2 7.75l2 1.25M5 12H2.75m2.5-3.25l-2-1.25m2 7.75l-2 1.25");
}

</style>
