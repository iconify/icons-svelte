<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd5wnvypl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:apps-plus-outline" {...props}></Icon>
<style>
:global(.qd5wnvypl) {
  fill: currentColor;
  d: path("M12.192 18v-3.808H20V18zM4 9.808V6h6.808v3.808zM4 18v-3.808h3.808V18zm7.192 1H21v-5.808h-9.808zM3 10.808h8.808V5H3zM3 19h5.808v-5.808H3zm14-8.192v-3h-3v-1h3v-3h1v3h3v1h-3v3z");
}

</style>
