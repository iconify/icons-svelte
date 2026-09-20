<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq--glbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:comment-bank-sharp" {...props}></Icon>
<style>
:global(.zq--glbpw) {
  fill: currentColor;
  d: path("m13.385 10.116l2-1.193l2 1.193V4h-4zM3 20.077V3h18v14H6.077z");
}

</style>
