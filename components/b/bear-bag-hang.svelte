<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eslgl7bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bear-bag-hang" {...props}></Icon>
<style>
:global(.eslgl7bzt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h19m-11 7.5c-5 2.5-5 10 1.5 10s6.5-7.5 1.5-10ZM12 3v7.5M17 3l2.5 2.5");
}

</style>
