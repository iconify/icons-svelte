<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ailo9ub1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:details" {...props}></Icon>
<style>
:global(.ailo9ub1p) {
  fill: currentColor;
  d: path("M2 21L12 3l10 18zm3.4-2H11V8.925zm7.6 0h5.6L13 8.925z");
}

</style>
