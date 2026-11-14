<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe-qfy1aa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pets-vs-cattle" {...props}></Icon>
<style>
:global(.xe-qfy1aa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h8v18h-8Zm11 0h8v4h-8Zm0 7h8v4h-8Zm0 7h8v4h-8Zm-8-10h2");
}

</style>
