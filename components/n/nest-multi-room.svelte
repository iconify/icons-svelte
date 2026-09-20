<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef4fxjtok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:nest-multi-room" {...props}></Icon>
<style>
:global(.ef4fxjtok) {
  fill: currentColor;
  d: path("m4 9l8-6l8 6zm0 12v-4h9v4zm11 0v-4h5v4zM4 15v-4h5v4zm7 0v-4h9v4z");
}

</style>
