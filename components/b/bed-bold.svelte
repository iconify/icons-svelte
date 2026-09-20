<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ia9tahadl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:bed-bold" {...props}></Icon>
<style>
:global(.ia9tahadl) {
  fill: currentColor;
  d: path("M212 68H36V48a12 12 0 0 0-24 0v160a12 12 0 0 0 24 0v-28h196v28a12 12 0 0 0 24 0v-96a44.05 44.05 0 0 0-44-44m-112 88H36V92h64Zm132 0H124V92h88a20 20 0 0 1 20 20Z");
}

</style>
