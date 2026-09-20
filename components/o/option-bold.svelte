<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="sn_e-idqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:option-bold" {...props}></Icon>
<style>
:global(.sn_e-idqo) {
  fill: currentColor;
  d: path("M236 192a12 12 0 0 1-12 12h-63.06a19.89 19.89 0 0 1-17.88-11.06L92.58 92H32a12 12 0 0 1 0-24h63.06a19.89 19.89 0 0 1 17.88 11.06L163.42 180H224a12 12 0 0 1 12 12M152 92h72a12 12 0 0 0 0-24h-72a12 12 0 0 0 0 24");
}

</style>
