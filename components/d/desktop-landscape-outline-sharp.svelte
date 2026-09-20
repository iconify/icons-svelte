<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdary4bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:desktop-landscape-outline-sharp" {...props}></Icon>
<style>
:global(.hdary4bfm) {
  fill: currentColor;
  d: path("M6 16h9v-5H6zm10.5-3H18V8H9v1.5h7.5zM2 20V4h20v16zm2-2h16V6H4zm0 0V6z");
}

</style>
