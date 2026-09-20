<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yee9k2bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:iframe-sharp" {...props}></Icon>
<style>
:global(.yee9k2bcc) {
  fill: currentColor;
  d: path("M10 15v-5h8v5zm-7 4V5h18v14zm1-1h16V8H4z");
}

</style>
