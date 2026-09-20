<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zklpa5btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:port-usb-c-24-regular" {...props}></Icon>
<style>
:global(.zklpa5btr) {
  fill: currentColor;
  d: path("M16 10.5a1.5 1.5 0 1 1 0 3H8a1.5 1.5 0 1 1 0-3zM16 9H8a3 3 0 1 0 0 6h8a3 3 0 0 0 0-6");
}

</style>
