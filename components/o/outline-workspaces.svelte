<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt0m7ib_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-workspaces" {...props}></Icon>
<style>
:global(.dt0m7ib_k) {
  fill: currentColor;
  d: path("M6 15c1.1 0 2 .9 2 2s-.9 2-2 2s-2-.9-2-2s.9-2 2-2m0-2c-2.2 0-4 1.8-4 4s1.8 4 4 4s4-1.8 4-4s-1.8-4-4-4m6-8c1.1 0 2 .9 2 2s-.9 2-2 2s-2-.9-2-2s.9-2 2-2m0-2C9.8 3 8 4.8 8 7s1.8 4 4 4s4-1.8 4-4s-1.8-4-4-4m6 12c1.1 0 2 .9 2 2s-.9 2-2 2s-2-.9-2-2s.9-2 2-2m0-2c-2.2 0-4 1.8-4 4s1.8 4 4 4s4-1.8 4-4s-1.8-4-4-4");
}

</style>
