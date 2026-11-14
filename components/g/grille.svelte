<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylrb_p1rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:grille" {...props}></Icon>
<style>
:global(.ylrb_p1rn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h16a1.5 1.5 0 0 1 1.5 1.5l-1.5 9a2.5 2.5 0 0 1-2.5 1.5h-11A2.5 2.5 0 0 1 4 16.5l-1.5-9A1.5 1.5 0 0 1 4 6Zm2 3h12M6.5 12h11M7 15h10");
}

</style>
