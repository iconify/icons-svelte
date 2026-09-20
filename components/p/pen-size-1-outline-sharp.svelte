<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex1p8jb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:pen-size-1-outline-sharp" {...props}></Icon>
<style>
:global(.ex1p8jb2q) {
  fill: currentColor;
  d: path("M5.187 18.814q-.13-.13-.13-.31t.13-.317l13-13q.136-.13.317-.13t.31.13q.128.129.128.31t-.128.317l-13 13q-.136.128-.317.128t-.31-.128");
}

</style>
