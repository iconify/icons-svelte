<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b6xmm6bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:keyboard-capslock-outline-sharp" {...props}></Icon>
<style>
:global(.b6xmm6bjb) {
  fill: currentColor;
  d: path("M6.5 17.5v-1h11v1zM12 6.292l5.308 5.308l-.708.708l-4.6-4.6l-4.6 4.6l-.708-.708z");
}

</style>
