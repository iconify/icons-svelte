<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfqtstlhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:details-rounded" {...props}></Icon>
<style>
:global(.sfqtstlhd) {
  fill: currentColor;
  d: path("M3.7 21q-.575 0-.862-.488t-.013-.987l8.3-14.95q.275-.5.875-.5t.875.5l8.3 14.95q.275.5-.012.988T20.3 21zm1.7-2H11V8.925zm7.6 0h5.6L13 8.925z");
}

</style>
