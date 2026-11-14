<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg8dykjou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:foh-position" {...props}></Icon>
<style>
:global(.dg8dykjou) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19v16h-19ZM8 11.5V17m4-5.5V17m4-5.5V17m-9.5-4h3m1 2.5h3m1-2.75h3M8 8h.01M12 8h.01M16 8h.01");
}

</style>
