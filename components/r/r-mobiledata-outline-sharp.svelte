<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j96fpbbdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:r-mobiledata-outline-sharp" {...props}></Icon>
<style>
:global(.j96fpbbdt) {
  fill: currentColor;
  d: path("M2 10V2h7v5.2H7.8L9 10H7L5.85 7.35H4V10zm2-4.65h3V4H4z");
}

</style>
