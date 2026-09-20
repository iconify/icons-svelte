<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fced2hbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:outdoor-garden-sharp" {...props}></Icon>
<style>
:global(.fced2hbbk) {
  fill: currentColor;
  d: path("M2 21h6V6L5 3L2 6zm7 0h6V6l-3-3l-3 3zm7 0h6V6l-3-3l-3 3z");
}

</style>
