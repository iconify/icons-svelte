<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5cr48bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:check-box-outline-sharp" {...props}></Icon>
<style>
:global(.c5cr48bgh) {
  fill: currentColor;
  d: path("m10.6 15.508l6.396-6.396l-.707-.708l-5.689 5.688l-2.85-2.85l-.708.708zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
