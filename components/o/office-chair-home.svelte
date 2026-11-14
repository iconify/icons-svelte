<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk__cfbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:office-chair-home" {...props}></Icon>
<style>
:global(.uk__cfbbn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 3l1 10.5h11.5m-6 0v4m-7 1.5l7-1.5l7 1.5m-14 2.75h.01m13.99 0h.01");
}

</style>
