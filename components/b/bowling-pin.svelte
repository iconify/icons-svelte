<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz7jixuzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bowling-pin" {...props}></Icon>
<style>
:global(.fz7jixuzq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 21.5h4.5c2.25-3.5 2.5-7.5-.25-11c-.75-1 1-2 1-5a3 3 0 0 0-6 0c0 3 1.75 4 1 5c-2.75 3.5-2.5 7.5-.25 11Zm.25-11h4");
}

</style>
