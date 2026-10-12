<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkozz7qpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:roof-shingle-sharp" {...props}></Icon>
<style>
:global(.rkozz7qpg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.75h5l1.25 3a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1-2.5 0ZM5.75 9.5h12.5l1.25 3a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1-2.5 0ZM4.5 16.25h15l1.25 3a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1-2.5 0a1.25 1.25 0 0 1-2.5 0Z");
}

</style>
