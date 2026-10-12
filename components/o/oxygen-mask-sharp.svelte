<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzwbi-b5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:oxygen-mask-sharp" {...props}></Icon>
<style>
:global(.gzwbi-b5a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 9h-4m14.5 0h4M12 3.25h2.25l.76 2.12l2.23 6.26l.76 2.12H6l.76-2.12l2.23-6.26l.76-2.12zm-1.5 7h.01m2.99 0h.01M12 13.75v5.75h9.25");
}

</style>
