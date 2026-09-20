<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0smrnbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:battery-android-frame-plus-outline-sharp" {...props}></Icon>
<style>
:global(.v0smrnbzx) {
  fill: currentColor;
  d: path("M1 18V6h15v2H3v8h13v2zm17-2v-3h-3v-2h3V8h2v3h3v2h-3v3zM4 15V9h9v6z");
}

</style>
