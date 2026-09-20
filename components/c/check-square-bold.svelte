<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xwz-5--fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:check-square-bold" {...props}></Icon>
<style>
:global(.xwz-5--fm) {
  fill: currentColor;
  d: path("M79.51 144.49a12 12 0 1 1 17-17L112 143l47.51-47.52a12 12 0 0 1 17 17l-56 56a12 12 0 0 1-17 0ZM228 48v160a20 20 0 0 1-20 20H48a20 20 0 0 1-20-20V48a20 20 0 0 1 20-20h160a20 20 0 0 1 20 20m-24 4H52v152h152Z");
}

</style>
