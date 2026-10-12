<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a64rl16rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:diverging-bar-sharp" {...props}></Icon>
<style>
:global(.a64rl16rj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v18.5m2.25-17.5h7v3.5h-7zm-9.5 6.5h5v3.5h-5zm-2 6.5h7v3.5h-7zm11.5 0h4v3.5h-4z");
}

</style>
