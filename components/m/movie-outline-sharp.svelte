<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f54_s7chs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:movie-outline-sharp" {...props}></Icon>
<style>
:global(.f54_s7chs) {
  fill: currentColor;
  d: path("M3 19V5h1.616l1.5 3h3l-1.5-3h2l1.5 3h3l-1.5-3h2l1.5 3h3l-1.5-3H21v14zM4 9v9h16V9zm0 0v9z");
}

</style>
