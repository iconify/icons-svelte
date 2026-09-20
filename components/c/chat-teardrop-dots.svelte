<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vqivfubjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:chat-teardrop-dots" {...props}></Icon>
<style>
:global(.vqivfubjw) {
  fill: currentColor;
  d: path("M132 24A100.11 100.11 0 0 0 32 124v84a16 16 0 0 0 16 16h84a100 100 0 0 0 0-200m0 184H48v-84a84 84 0 1 1 84 84m12-80a12 12 0 1 1-12-12a12 12 0 0 1 12 12m-44 0a12 12 0 1 1-12-12a12 12 0 0 1 12 12m88 0a12 12 0 1 1-12-12a12 12 0 0 1 12 12");
}

</style>
