<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhs3fmblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:alpine-butterfly-knot" {...props}></Icon>
<style>
:global(.rhs3fmblo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10.5c-3-6-8.5-6-8.5-2c0 3 4.5 4 8.5 2m0 0c3-6 8.5-6 8.5-2c0 3-4.5 4-8.5 2m0 0l-5.5 9m5.5-9l5.5 9");
}

</style>
