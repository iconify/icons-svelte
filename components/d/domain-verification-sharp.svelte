<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1bstcd_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:domain-verification-sharp" {...props}></Icon>
<style>
:global(.q1bstcd_o) {
  fill: currentColor;
  d: path("m10.95 16.55l5.65-5.65l-1.45-1.45l-4.2 4.2l-2.1-2.1L7.4 13zM4 8h16V6H4zM2 20V4h20v16z");
}

</style>
