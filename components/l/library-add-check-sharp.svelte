<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhdkt4lck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:library-add-check-sharp" {...props}></Icon>
<style>
:global(.vhdkt4lck) {
  fill: currentColor;
  d: path("m12.2 13.32l4.958-4.959l-.708-.719l-4.25 4.25l-2.15-2.138l-.708.708zM6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>
