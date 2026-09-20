<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qltp1pcqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:fast-reverse-button" {...props}></Icon>
<style>
:global(.qltp1pcqe) {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M121.76 29.01L66.84 60.72V29.01L6.24 64l60.6 34.99V67.28l54.92 31.71z");
}

</style>
