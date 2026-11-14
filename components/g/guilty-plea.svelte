<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqj76ubzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:guilty-plea" {...props}></Icon>
<style>
:global(.rqj76ubzl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.768 7.036l3.464-2l4 6.928l-3.464 2ZM9.25 8.5l8.75-5m-6.5 15.2V21h-9v-3.5h8.8m3.45.5l2 2L21 15.75");
}

</style>
