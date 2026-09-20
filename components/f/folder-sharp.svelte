<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohawklu8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:folder-sharp" {...props}></Icon>
<style>
:global(.ohawklu8u) {
  fill: currentColor;
  d: path("M3 19V5h6.596l2 2H21v12z");
}

</style>
