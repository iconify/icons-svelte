<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjvkfnb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:indent-sharp" {...props}></Icon>
<style>
:global(.fjvkfnb6y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.5h16.5m-9 5h9m-9 5h9m-16.5 5h16.5M3.75 12h4.5m-2-2.5l2.5 2.5l-2.5 2.5");
}

</style>
