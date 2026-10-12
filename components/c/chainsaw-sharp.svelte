<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rk_mvacjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chainsaw-sharp" {...props}></Icon>
<style>
:global(.rk_mvacjt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8h8.5v9h-8.5zm2 0V4.75h5.5V8m1.25 2.25h9.75V15H11.5zM14 12.6h4.75m-13.5.9h3.5");
}

</style>
