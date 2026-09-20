<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ax416ervf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:fluence" {...props}></Icon>
<style>
:global(.ax416ervf) {
  fill-rule: evenodd;
  d: path("M11.35 3h1.368v3.02a6.024 6.024 0 0 1 0 11.96V21h-1.369v-3.011a6.024 6.024 0 0 1 0-11.977zm0 4.392a4.655 4.655 0 0 0 0 9.217zm1.368 9.207a4.655 4.655 0 0 0 0-9.197z");
}

</style>
