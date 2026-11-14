<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k56oaebhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:canned-drink-crate" {...props}></Icon>
<style>
:global(.k56oaebhr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11h19v10h-19ZM4 11V5l.75-1.5h2L7.5 5v6m2.75 0V5L11 3.5h2l.75 1.5v6m2.75 0V5l.75-1.5h2L20 5v6M9.5 15.5h5");
}

</style>
