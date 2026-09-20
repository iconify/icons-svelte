<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gooeucbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-justify-flex-end-outline" {...props}></Icon>
<style>
:global(.gooeucbxo) {
  fill: currentColor;
  d: path("M20 22V2h2v20zm-6-5V7h3v10zm-6 0V7h3v10z");
}

</style>
