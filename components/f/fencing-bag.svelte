<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnk-db7xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fencing-bag" {...props}></Icon>
<style>
:global(.dnk-db7xk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11h14a2.5 2.5 0 0 1 2.5 2.5v4A2.5 2.5 0 0 1 19 20H5a2.5 2.5 0 0 1-2.5-2.5v-4A2.5 2.5 0 0 1 5 11Zm.5 0V9.5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2V11m2.5 0l6.5-7.5m-4.5 2l3 2.75");
}

</style>
