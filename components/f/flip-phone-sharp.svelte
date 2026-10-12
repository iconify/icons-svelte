<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgo9j_opj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:flip-phone-sharp" {...props}></Icon>
<style>
:global(.pgo9j_opj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 2.75h11.5v8H6.25zm3 4h5.5m-8.5 6.5h11.5v8H6.25zm3 3h5.5m-5.5 2.5h5.5");
}

</style>
