<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvkgekbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-justify-space-between" {...props}></Icon>
<style>
:global(.cvkgekbcz) {
  fill: currentColor;
  d: path("M20 22v-5h-3V7h3V2h2v20zM2 22V2h2v5h3v10H4v5z");
}

</style>
