<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7qfy844x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:pentagon-outline-sharp" {...props}></Icon>
<style>
:global(.d7qfy844x) {
  fill: currentColor;
  d: path("M7.085 19.5h9.83l3.306-9.917L12 3.835L3.779 9.583zm-.72 1L2.597 9.192L12 2.616l9.404 6.576l-3.77 11.308zM12 11.667");
}

</style>
