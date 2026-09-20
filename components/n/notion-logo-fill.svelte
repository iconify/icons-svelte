<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="kj_k3kbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:notion-logo-fill" {...props}></Icon>
<style>
:global(.kj_k3kbog) {
  fill: currentColor;
  d: path("M224 48a8 8 0 0 1-8 8h-16v152a8 8 0 0 1-8 8h-40a8 8 0 0 1-7-4.14L72 79.15V200h16a8 8 0 0 1 0 16H40a8 8 0 0 1 0-16h16V56H40a8 8 0 0 1 0-16h64a8 8 0 0 1 7 4.14l73 132.71V56h-16a8 8 0 0 1 0-16h48a8 8 0 0 1 8 8");
}

</style>
