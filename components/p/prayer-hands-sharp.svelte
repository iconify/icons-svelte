<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nb1x3m3gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:prayer-hands-sharp" {...props}></Icon>
<style>
:global(.nb1x3m3gr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 18V3H7v7.25l-2.25 1.5v5.125L6.25 18Zm3 0V3H17v7.25l2.25 1.5v5.125L17.75 18Zm-7.25 3h11.5");
}

</style>
