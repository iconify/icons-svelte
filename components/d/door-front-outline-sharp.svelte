<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kplxa0bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:door-front-outline-sharp" {...props}></Icon>
<style>
:global(.kplxa0bsq) {
  fill: currentColor;
  d: path("M4 20v-1h2V4h12v15h2v1zm3-1h10V5H7zm7.23-6.23q.31 0 .54-.23T15 12t-.23-.54t-.54-.23t-.539.23t-.23.54t.23.54t.54.23M7 5v14z");
}

</style>
