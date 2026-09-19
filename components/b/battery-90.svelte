<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frfc9qb1r"/><path class="na88tbcbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:battery-90" {...props}></Icon>
<style>
:global(.frfc9qb1r) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 5.33C17 4.6 16.4 4 15.67 4H14V2h-4v2H8.33C7.6 4 7 4.6 7 5.33V8h10z");
}

:global(.na88tbcbz) {
  fill: currentColor;
  d: path("M7 8v12.67C7 21.4 7.6 22 8.33 22h7.33c.74 0 1.34-.6 1.34-1.33V8z");
}

</style>
