<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1a9qg5xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:overview-key-sharp" {...props}></Icon>
<style>
:global(.e1a9qg5xt) {
  fill: currentColor;
  d: path("M1.77 18V6h12v12zM17 18V6h1v12zm4.23 0V6h1v12z");
}

</style>
