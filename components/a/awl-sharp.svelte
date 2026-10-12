<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pivx2xbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:awl-sharp" {...props}></Icon>
<style>
:global(.pivx2xbvy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.68 11.2l-3.01 3.01c-.71.7-2.3-.18-3.36.88a3.25 3.25 0 0 0 4.6 4.6c1.06-1.06.18-2.65.88-3.36l3.01-3.01l.343-.35l-.343-.35l-1.42-1.42l-.35-.343zm-1.31 1.31l2.12 2.12m.6-2.72l8.66-8.66");
}

</style>
