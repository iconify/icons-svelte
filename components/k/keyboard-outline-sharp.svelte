<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lp4a6lyns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:keyboard-outline-sharp" {...props}></Icon>
<style>
:global(.lp4a6lyns) {
  fill: currentColor;
  d: path("M3 18V6h18v12zm1-1h16V7H4zm4.23-1.23h7.54v-1.54H8.23zm-3-3h1.54v-1.54H5.23zm3 0h1.54v-1.54H8.23zm3 0h1.54v-1.54h-1.54zm3 0h1.54v-1.54h-1.54zm3 0h1.54v-1.54h-1.54zm-12-3h1.54V8.23H5.23zm3 0h1.54V8.23H8.23zm3 0h1.54V8.23h-1.54zm3 0h1.54V8.23h-1.54zm3 0h1.54V8.23h-1.54zM4 17V7z");
}

</style>
