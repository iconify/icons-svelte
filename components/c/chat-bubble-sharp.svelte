<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrhtr9bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:chat-bubble-sharp" {...props}></Icon>
<style>
:global(.yrhtr9bqg) {
  fill: currentColor;
  d: path("M2 22V2h20v16H6z");
}

</style>
