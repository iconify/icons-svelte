<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9o7aacbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-android-frame-bolt-sharp" {...props}></Icon>
<style>
:global(.d9o7aacbe) {
  fill: currentColor;
  d: path("M1 18V6h17.05l-1.6 2H3v8h12.825l-.375 2zm16.675-1l.7-4H15l4.8-6h.525l-.7 4H23l-4.8 6zM4 15V9h11.65l-4.8 6z");
}

</style>
