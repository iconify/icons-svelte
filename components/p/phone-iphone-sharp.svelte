<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f67mqyb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:phone-iphone-sharp" {...props}></Icon>
<style>
:global(.f67mqyb3f) {
  fill: currentColor;
  d: path("M6 22V2h12v20zm6-1.961q.31 0 .54-.23t.23-.54t-.23-.54T12 18.5t-.54.23t-.23.54t.23.539t.54.23m-5-3.5h10V5.5H7z");
}

</style>
