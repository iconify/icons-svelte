<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsqqywzve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:deposit-interest-paid" {...props}></Icon>
<style>
:global(.wsqqywzve) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.1 21.5H4.5v-19h15v10.1M8.5 2.5v19m3-14.5h4m-4 3H14m1.25 10.75l5.5-5.5m-5.25.25h.01m4.99 5h.01");
}

</style>
