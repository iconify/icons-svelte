<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7auo5bya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:carry-on-sharp" {...props}></Icon>
<style>
:global(.g7auo5bya) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 8.75v-6h4.5v6m-8.5 0h12.5v10.5H5.75zm0 4.75h12.5m-9.5 5.75v2m6.5-2v2");
}

</style>
