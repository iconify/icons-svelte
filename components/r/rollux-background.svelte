<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="b2voj68ta"/><path class="oulmcpo7w"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:rollux-background" {...props}></Icon>
<style>
:global(.b2voj68ta) {
  fill: var(--svg-color--dbef88, #dbef88);
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 .002 16");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.mumfproca) {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

:global(.oulmcpo7w) {
  fill: var(--svg-color--000, #000);
  d: path("M8.466 7.87h.331l7.93 7.27v.991h-8.26zm6.255 4.796a3.304 3.304 0 0 0-4.691-4.3z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
