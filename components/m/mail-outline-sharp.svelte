<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpqbhosqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:mail-outline-sharp" {...props}></Icon>
<style>
:global(.mpqbhosqj) {
  fill: currentColor;
  d: path("M2 20V4h20v16zm10-7L4 8v10h16V8zm0-2l8-5H4zM4 8V6v12z");
}

</style>
