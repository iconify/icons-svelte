<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3z-wsbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lamp-off-sharp" {...props}></Icon>
<style>
:global(.g3z-wsbmh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 3.25h6.5l.37.93l2.76 6.89l.37.93H4.75l.37-.93l2.76-6.89l.37-.93zM12 12v8.75M8.25 21h7.5");
}

</style>
