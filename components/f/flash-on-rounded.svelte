<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymrhg_baa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:flash-on-rounded" {...props}></Icon>
<style>
:global(.ymrhg_baa) {
  fill: currentColor;
  d: path("M11.121 17.265q-.121-.16-.121-.376V13h-1q-.671 0-1.143-.472t-.472-1.144V4.617q0-.672.472-1.144T10 3h3.83q.686 0 1.125.5q.44.5.259 1.116L14 8.789h1.606q.727 0 1.068.636q.342.637-.068 1.252l-4.5 6.56q-.131.186-.31.242q-.18.056-.367 0t-.308-.215");
}

</style>
