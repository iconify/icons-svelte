<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmw-mac6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:keyboard-hide-sharp" {...props}></Icon>
<style>
:global(.nmw-mac6n) {
  fill: currentColor;
  d: path("M12 21.846L8.923 18.77h6.154zM3 16V4h18v12zm5.23-2.23h7.54v-1.54H8.23zm-3-3h1.54V9.23H5.23zm3 0h1.54V9.23H8.23zm3 0h1.54V9.23h-1.54zm3 0h1.54V9.23h-1.54zm3 0h1.54V9.23h-1.54zm-12-3h1.54V6.23H5.23zm3 0h1.54V6.23H8.23zm3 0h1.54V6.23h-1.54zm3 0h1.54V6.23h-1.54zm3 0h1.54V6.23h-1.54z");
}

</style>
