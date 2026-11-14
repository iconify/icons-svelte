<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tezlx-nil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:precipitation-amount" {...props}></Icon>
<style>
:global(.tezlx-nil) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 2.5c1.75 2 2.5 3.25 2.5 4.25a2.5 2.5 0 0 1-5 0c0-1 .75-2.25 2.5-4.25Zm-12.5 4v13a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-13m-6 3.5H7m-2.5 3H7m-2.5 3h6");
}

</style>
