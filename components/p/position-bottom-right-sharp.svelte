<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rysd8ybww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:position-bottom-right-sharp" {...props}></Icon>
<style>
:global(.rysd8ybww) {
  fill: currentColor;
  d: path("M9.385 16.808h8v-2h-8zM4 20V4h16v16z");
}

</style>
