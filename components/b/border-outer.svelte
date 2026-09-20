<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2iqzxb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:border-outer" {...props}></Icon>
<style>
:global(.g2iqzxb8e) {
  fill: currentColor;
  d: path("M5 19h14V5H5zm-1 1V4h16v16zm3.692-7.384v-1.231h1.231v1.23zm3.692 3.692v-1.231h1.231v1.23zm0-3.692v-1.231h1.231v1.23zm0-3.693v-1.23h1.231v1.23zm3.693 3.693v-1.231h1.23v1.23z");
}

</style>
