<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gsqsbsbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:alcohol-marker" {...props}></Icon>
<style>
:global(.gsqsbsbks) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.277 18.541l9.546-9.546l3.182 3.182l-9.546 9.546Zm10.077-9.016l2.828-2.828l6.01-1.768l-6.717 6.717Zm-6.895 5.834l3.182 3.182");
}

</style>
