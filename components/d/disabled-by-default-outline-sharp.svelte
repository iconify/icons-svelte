<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgc05pior"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:disabled-by-default-outline-sharp" {...props}></Icon>
<style>
:global(.dgc05pior) {
  fill: currentColor;
  d: path("M5 19h14V5H5zm-1 1V4h16v16zm4.4-3.712l3.6-3.6l3.6 3.6l.688-.688l-3.6-3.6l3.6-3.6l-.688-.689l-3.6 3.6l-3.6-3.6l-.689.689l3.6 3.6l-3.6 3.6zM5 19V5z");
}

</style>
